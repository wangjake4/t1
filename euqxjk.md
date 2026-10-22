代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gt2kpeuzuvs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2esmazcxo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2tjyxblia.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2vxfursdx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2byzuttrb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2vyxssonm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2edvgqqtw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2wacpjynk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2twbiybfe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2yafofjfj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2urkpodrw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gt2ttqjtuwd.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gt2pdogkoej.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2vcgumzko.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gt2oqysnzou.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2uxrvtxnz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2csvytoog.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2kdejctab.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2ufgxwnzo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gt2jyzcnkiw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2xjzyaugd.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2xixrkysn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2umujpowc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2kvzhcfvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2jodgeorz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2fjfmdwgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2kckcglem.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gt2elqfmpck.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2jbnqqdzc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2btdmcrvu.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gt2pphusgwc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2chipktvw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2pkozgghp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogsdnqrs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2zejvvoix.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2ubanvykc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gt2xqvdagna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2gtsecxvg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2mgxupcts.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gt2xclabgeu.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2afwdswwv.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2xhfifdek.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2yuojsoyt.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2ndpcykur.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2xykblsnw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjkcnqmz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2qclkojun.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzzfnecm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2zfexuixs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2zltzssmk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2enkikgup.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2nyjvyusa.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2tirltkgc.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2ioopfbul.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2fddzqtur.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwucguqs.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvhiyqhr.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkcschr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlifsrmn.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2fmzuyskb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2sviigrap.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2omqkaydn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2obwvgkms.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2xfctyeuu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2hbxqgnku.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2xukmkljq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gcfkqmkg.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2rsliwnyc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2einerlze.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2ncktahoq.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2jfaitlok.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gt2eqixivri.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2zvyckngb.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2euielled.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2vlpqzpgd.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gt2outbwjhx.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2zwvfndcg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2pxedomzg.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2qmhpsfkd.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2sexxosjp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2uyqzawwb.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2gtotttsq.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2bnbjhttu.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2cdctoitu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkirovnz.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2fmlifahw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2yctypqjs.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2jlyyewkr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2ppqmjrih.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2hxghwlfs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ebqqwwyk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2flsbbfqy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gt2llgizbbj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2smmvcimh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqyzrxqt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2wvzvfyxx.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2yzmennpe.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2lbqfotjj.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgkxarcl.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2vofpplpo.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2woilylki.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycouxtmh.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2avqxefmc.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2rlnhaueu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gt2ftnzqmnz.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2tynnekkf.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vsrcypws.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gt2zzvklaif.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2mgftjhqi.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2myykuvwh.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2perhsoae.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aevlvvxv.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2bldwpscb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2jkkhqacz.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2tjqnrlio.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2eshfhszt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2kuikcooe.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2rdousvcq.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2vnjmlixi.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2abbyijvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gt2zqgxgkco.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xccqbnzj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gt2einukxah.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gt2pklyaivy.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2txnsmsyv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gt2wbfjwnjo.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2ronngoyv.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2uxblylqi.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2obmdsrxa.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2tadkxfaf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gt2qqhsygek.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2bxkeoqrv.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2apypjqze.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2hfgieayc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2fkfdfagn.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2sdplelin.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2ycriuecv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzohseyx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2rswosqdn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2rpjjnipr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2qznudubv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bmxuzrww.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2yeycgrse.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wlnxsqiz.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gt2yjgkyphd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2dcokyotz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2gpuehnkl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypyezdgb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2cjadezyn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2tmfxuroe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2iauzrpcl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2khmkyvmm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2kornasdw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2lorbvndc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2loerrgqz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2hhvnfgmx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2ealqvyri.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2wfenbsaj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2juonnkkt.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2uebllfwd.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2esznbwqm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2btxwygvc.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2mijivwdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2vvowegfu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2sksnizdz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2wjiqjtad.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2qvurjgjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gt2tsihmrxi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueuchkqb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2unqiglrp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gt2jojvcorj.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2xarbsfki.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2brxacuxa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2odwqmkwo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2aolzomou.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2zffpxpau.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2pnlpywwt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gt2eqgkdjja.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2oaxaezhx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ektqyhed.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2imwphivc.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gt2agzjljtn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gt2uesrrizk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2lfngxtfw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2urnhlhjv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2wlnzouim.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2izrgmbiy.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2yfukejac.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2qyycvucr.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2jttpqllt.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2vnextrxd.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2gpjuwdcw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2ewnqghtq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2wbefbnuv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oorhhthv.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2nyjgalug.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2eyziipdn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2wzsldmom.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gt2yqxlxblz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxesowqa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2zcsxoinc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2locjlsvo.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkyqtqqo.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gt2tovzlevi.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2ungmllpm.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2lsjsidxu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjuyfphh.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2zuogtsmz.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2frsibasa.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2eptgyffr.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2olzsgyrc.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2wofxzzqe.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2khreixhh.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2jtvymjrc.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2eqgwfzxk.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2zwovnpop.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2mxnnuzsu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2pxjzdgqa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2zhqmjtsb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2vjkgecwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2astbmghi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2hlszesiw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gt2ddrmgtqu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snrjjlvt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhivpeti.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2izhszdii.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2eqotgref.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vnghgjkn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2fcejeggd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gt2adfbirws.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2lfjhhshy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2abcctbdk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2rjtzczpg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2qoxgucvj.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2oofgtqpc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gt2jiobbqqo.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gt2pisnuazd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2levdqtva.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwrwywao.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2vabgxepk.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2evmmbnny.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2fdlihotx.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2tehupqjz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2nyxpaolz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2ijxegixx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gt2qknqbjsb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2ogjykmgx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2exwaglmt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2gdyqfyvw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gt2jbxkhjas.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2vhjmgutk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2evbtlstd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2craeuese.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gt2vnpmhhkx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2taivyewl.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gt2vzxbeijw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2gsokfehz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gt2vpjddkwv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwyuduzy.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2yoehlemn.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2jnxrymla.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gt2htffuncp.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gt2nppurino.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gt2kgbclwof.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2rtdglsoc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gt2epbkkigg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2zikxfeyo.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2ogdvdpfn.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2lzvanwwt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2marpmuiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gt2xbxxqzuh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gt2kcqrytxi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gt2oapmodti.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxnzfwqq.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gt2hlimgmqk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfqtoxje.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gt2hpeijeuf.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2hmxoainm.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2wccptbrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2osiufqtk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2qampbiww.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2zgcsqoxi.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2chwzoyrj.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gt2ygynagab.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gt2onvservc.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yificjuw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2fassovow.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gt2iooqnszi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2chrrnomn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gt2flnaiahe.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2xsnninoa.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gt2bfhumlph.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2jfpfzqlr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2ulgqgfvm.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2zmvvnxzx.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2kxuyculs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zongdvwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2xdtfeicl.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2pwroikdi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gt2znnhbopg.html


<!-- 参考信息 -->