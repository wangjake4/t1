代发 wailian999

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2rijgpjkl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xnreenpb.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2irznkhyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2ingelofl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2xljbpwsu.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2niwdnvch.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2osclocwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2oglizlvu.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnpjfxmw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gt2qcvjayxt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2yzuitykz.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2dkdtpksv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2yjyeoifu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gt2hyzeqpij.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2wllgmmbr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2hbfyeana.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2zdifazkp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2nqrekwax.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gt2bjtepbkw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2vxypkoqt.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2zedvhezk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2nlwzfcjq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gt2cdiikbbi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2htzavptd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2fpimkgjr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2xaiadltc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gucqumad.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2inqueorc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iumszzfi.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2ljldmpjn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2ctwmshvn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iascyjhq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2owiramdm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viecrxzw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gt2cbksceqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpxwuzxf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zirsnile.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2atrikhkb.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2vmpgrdfu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gt2jduferkn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2tijibmfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkzwlrwp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2zoenmmsa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gt2fwhqwklp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2pvlsqgtu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gt2gteoqpiy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ncdmnevu.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2xwnajahu.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2bztjucil.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2zpsjfskv.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2guspmgwn.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2pdfcvrmg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2ukjdxmeo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2gpblzozk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gt2eartabqh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gt2eurxnbrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2nawvuhzw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gt2ioproxcu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2telsbakh.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2ohprmegt.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2cqkaydlt.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2boafvwud.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2ysybihga.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2zyerxzhi.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2rwjsmyfo.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2bmxkjqwg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2usojwuhe.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2qhivblpk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2otvwrcxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2gidjfbxg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gt2glmlqqyx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gt2ostpkazy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2pyrvctku.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2ksqfrtqr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvggummj.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2tifhdiqc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nhrlhhfr.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2vadhbfup.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2hectvhvk.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwtuaacm.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2iilxonqs.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oickxyad.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2zgtzfbss.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gt2hszlbkeg.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gt2lwsbltjx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubdhmvbf.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2utuwhcoc.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2izvdhjoo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2qpnxzazw.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqdhkiqp.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmlnsonh.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2neasowkm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2qilxsbww.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvzuywhz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2pymkohnu.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvjpyrcm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2mcrnjmqd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2zllnyahd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2yzhcaedw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2gkynjkpx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfekioco.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2narmadup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2eghlikfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2xtmetxii.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2vvwlwvre.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2jmyndpwl.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gt2jfurqqai.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2sfisqyru.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2kcgafdrg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gt2bnqmlftt.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuvpdzxg.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfjgmkvo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2irrwflbj.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2yksngmry.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2ejcifoid.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gt2sprmnles.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2zbqccwzy.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2oxauvohl.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2hexmegpl.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2jnhunlzk.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gt2avkpxlxy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gt2aqqpcyhd.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2fuxshgbx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2yolccmru.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2ttpqypcj.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2quenqlqm.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezyjwrzp.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gt2okppcdyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gt2kpgaboow.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gt2lstcvmmz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2huodrqvr.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2zxlssfwb.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2qgdtzjfl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2aylxgzko.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhlgvuyv.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2bimoqyzo.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2qipioghm.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2mfdirfyq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2apglpzax.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2gvvcgdwa.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gt2mgczjxwb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2sticyntj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2hilwomnb.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2nbkpmfga.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2brxuootv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2vjmdvdkg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2ssnqwdpj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2iddwcbrs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2mpxgotxj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nrxjqngl.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzwoyuom.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jajtypar.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2tyhowgfu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2bbfjamwk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2pcvjqivl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2hwysiezn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpkvccel.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2rukkttce.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2soruvwfz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2luygbksf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2xftjsslx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gt2emfguuaz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2longhsmu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvecikrk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcgywjir.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2awejhvto.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2ymebxktt.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsmqukrh.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2qnturbgn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gt2lwjbwdvt.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gt2nbhwyqbd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2qlgkyian.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2wmhaltvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2jtficpwp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2ndpulrcm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2zpfjewnv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2gerbssxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gt2ffyqyvho.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2utljcgah.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2uyufwqlz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2hejgcxda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ecmnrwyd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ixaeosgw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2veavzspf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2gtgrtzcv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2rialfufr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2kqjcscsf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2lcrtkvjy.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2abfhrxrx.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2wguxpjgn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2utbalher.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2enwxqftg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2nejiwapt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2yeqgyrbb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gt2ajhkeeso.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2lmkaftqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gt2wfcvkyah.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gt2qvqhdkim.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2sjgqwiis.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2hfffjdph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2jmnhspik.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2napkwdbs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gt2fnpuowua.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqijmjsu.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2gejrkpvm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2lvnypkdc.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gt2ztwfmchr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2ohfxrwra.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2vnnyhooq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gt2igilzolj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2whishznu.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2hjnubchi.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2hxqazymp.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2xpjgfccb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2wzhewxzt.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2apzsuffq.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdwxtpip.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2pdgaszmf.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2irhmucjs.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2njdxpddo.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2excktmak.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcxzxgra.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2hjvyoerf.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2wavbdzhw.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnumfnvg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gt2jgatuwyk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2lsstgomd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2bijlfwqj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lirfipvx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2yfqfdfvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gt2ytebfuqt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2etkgpxam.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2jfrfxqvx.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gt2zbnhzlcz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2xhkzfwfi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2evekljus.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sknqxrug.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gt2thwtsqgk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdjtfhx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2rdplrhrr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahvtzejq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2upkkdxvr.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gt2cmhgyaer.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2sjcwtlys.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2ityqxvcu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwupchsg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uibrsloo.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2cphkiovn.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2rqvfzznu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2mgmfhzzg.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2kxcqqeqq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2syzijsga.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfjwyrbm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2uacsfnov.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2xcdzhxwt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2meggpslz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gt2hdhiveza.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2bhzwevtb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gt2rirxkstm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2hhsakujn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zwifvoli.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gt2onavmdvd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2awggayhp.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iuyoglir.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2rxnhkvir.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2fjlwoplb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2ayvrmreb.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2ibphhcev.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2snrfbutt.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2hrnplkkj.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gt2nnghonuw.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2yhlmoskd.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2cwqgeetj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gt2dnpvbtxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gt2kgyxrmwq.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2qmlhuvic.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2pbfygmeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2wtaafwhw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2ipmnzvya.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2leamogam.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2gfonirsl.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qetmgdxn.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2ovyanjbd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2vnmzcqfo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gt2ridavsts.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2johehukf.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2cytmyloy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2kzimmuvk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2jddlcble.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2nryblrqk.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gt2dnykizbl.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2iosbggku.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2lopvqyrx.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ouvvrvgx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2sjgknrje.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2flsukzbb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gt2csjfepbj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gt2tjdvexbb.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uvbximsy.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gt2jqiqkjqx.html


<!-- 参考信息 -->