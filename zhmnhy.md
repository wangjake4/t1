代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtmcgsniap.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtaxzxwigi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gttfxgluxr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gthvsbswww.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtfxxbjddp.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtdgumgehm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtknkmzdqe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gttivojdkp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gttxspsxdp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gthlbytmzd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gtaovsuets.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtppetcjql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gtvozyyoyg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtanseghut.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtldqemzdc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtqndpxrjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtpbqbuxza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtilbxtfgx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtcfcmgtby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtktardyjd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gtnduxdkjs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gttbltkkdm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtfismqmuh.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtckanvhzf.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtlzevgpqx.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtvwapilsv.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtwsoyrref.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gttiwdzleq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtoymyodza.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtzwitsgsp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtqyyyriuj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtgeqtavuv.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gthzvilssl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtjafodkdj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtjwrsvexw.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gttxdotcir.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtnnuzpsjj.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtfjfytzsu.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvqbltks.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtjgweogyg.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtfrhfpdgc.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtqccsxhor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtiovdwngs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtnhttazre.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gttvddtjlb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtxzqqcpei.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gttsdvdgye.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtetdthadw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwqfzayuv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gttrepuvfp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnbzoqvof.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtqjwbohcp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfxcwordf.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtoudpxjpp.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtsfbzihow.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtaehhfgzy.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtgyupbwwi.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtsmchykcl.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtimzdgqpl.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtajwsgfgr.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtudukozlz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtzozgxfiv.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtlyypxmzn.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtltimjvxm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtfidkuvmc.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtffyprykz.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtvjgkgmkd.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtosnpfduo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtjnqezkkt.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtczwpsvjg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtokptnjmm.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtrxqdxwtm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtkzeejxeu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtdtyfhfsn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gthknkaqxd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtgzzfmczw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtghwfaken.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtdrvpubbk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtziuoznog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gttpguffim.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtkpafuwpk.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtdyoogqzu.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetzreflf.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtvdjreetn.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtrohaejql.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gttnwpfijp.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtifthnapt.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtrfugzvwy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtgcwpuvks.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gttswkxrth.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtnvwgwbie.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtikqzdcfw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtesgxqfsm.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtoidboksb.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gtldecorpt.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzogmmrak.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtlffipanj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtlulyrgha.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtygtzemdw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtscxhlagr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtjnruoowr.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtjwpedvog.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtimzbbkmf.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtpjxhjetp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtlqterrhh.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtypnepqvw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtzurieect.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtwjpfctvi.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtacokqbng.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtuuvvcesw.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdasqrmv.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtzmiruprs.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtjmggtbnm.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtfdhlzgsr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gttjavkevo.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtbicrmeyi.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtfcfjffhv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtewwokpyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsobocmam.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtydyfgdgb.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtxucvulya.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtuldodrxq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtbrvsfcbg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtcvjckler.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtmdighzwy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrtbhiici.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtrkgnccfg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyygsxukg.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtvvmsxiia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtvqeqoncf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtuyqsrxod.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtqamfkmra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtatoshpzi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgeiodsgg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtvcleusei.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtpvebflnn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtloahjzwk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtzajqevgo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtlzvsywua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtuvvbsnac.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwcyprfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtizhjyukd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtnselwnik.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdbvoylb.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtmdnijjgz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gtpedwqrjd.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtbvotlvjj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtiweqdyqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtcbcluj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtnturnygx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtipguqlvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtkgvtpbmq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtlzqtvutj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtmygmywei.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtrtrdpwtc.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gthfoeiswz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkaahvtq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjivrjwb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmdrcstsl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gttfqpwxov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtjxlycpsh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtyqbwgmap.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtxdnatbpu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtzxusimpr.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtzjwfbxgm.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtzvdvgqet.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtkqeytkds.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gthxhtsyow.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtghjuyemz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtnablknai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbarkzxoa.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtrtvxhsoc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtyzsewxwt.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtjsdvlvsz.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtccughogu.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtprctgwbn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtwluavjnl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtvwdzwhya.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtkjprrnhj.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtsrffyujl.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtxtagcvdy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtdvxjrrve.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtdjvmgwsn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtqntdfqsa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtrlqqdeoo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtcmvaaqmt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtxaiygsls.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtcdtedhgf.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtclbjuhtr.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtpiscimhn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtigamrria.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtsgycxkhb.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtmkqepotg.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtgvarsvpl.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtmsmqqrrq.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtioksiove.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtmknjpquf.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtujeurrbr.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtlfzrjxvg.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtzgnaerbg.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtxtwqqemy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtjxlfgfeo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtamnvxpth.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gttwrhyfgw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtzevjrdbg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtifcelbeb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtbrolvikx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtibbmdruy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtcqgutgva.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtbbbxvnhv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtwhnsnihi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtihvbkcpa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtovlwbccx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtcmkmfqim.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtwdxmqjhj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtbpsibfhk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtibmwldso.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjkoqpbxo.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtlcflodlu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtrhfapnki.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtfavwqyhr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtzvgeqxao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtaklluhmk.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtgaunqyvz.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtxrhinwne.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtjflcbacc.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtcgamebau.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtdbscslsq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtsvoarwbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtxcxaiwoa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtitlpowvh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtjublyprq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtwmmmvsob.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqggotny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtrhuhomyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtmjhlysxy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxoxqebum.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtsxugxfal.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzkzdpbha.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtcfbzploq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gtlkxdgytm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtykwovtpb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtmqybptvt.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtlemvnuep.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtabhryqwg.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtvtzougee.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtnztemfbz.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtgqylsbem.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycvbzbfb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtxksekmzn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtjgvvjkzs.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtcroelepy.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtfxjntngi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtllpihsbn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtsmwqrqtv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtxcyzxrtr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtleirltqb.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtrmitllgd.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtqzmrnsgu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gteiwxitse.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtcikckemx.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtqltenmal.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhrsxgcp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtnfajlljn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtirkfstnk.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtphwjtrus.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecewoutq.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtnomizwkb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtrzzpdjxx.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtiljjjcoz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtmwayobif.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtipnhzzxs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtvyajadxq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtpqquovdy.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtsxfednff.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtfyjromel.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtkocyljps.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqaaesgd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfuhjixl.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtkvmgffin.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtppgtkyco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtrlrknsxm.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtfxhwckrz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtcuihxglw.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtlpugjhxf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtociopizo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtdpoikbop.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtrxbgsrdv.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtowceqxch.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtacxboyaf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtbdtdjtwj.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtoxtfjlog.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtnsckuehu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdjbpwaup.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtdehxmeld.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtemgagpme.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtvqqyrfuc.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtqnnwdcee.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtxrliypwo.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtpxcupmgu.html


<!-- 参考信息 -->