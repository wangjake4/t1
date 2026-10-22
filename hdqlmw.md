代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtwulexfkf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtwzqmurdu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtixmaieac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojbkwuzo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gthfphsdjz.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtcjpuguum.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gttwlljgnb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtnaarzokq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtbyuoddyw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtlbcbdczp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtzwllbqbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtqnekudtv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtopahkntc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtezixxyrn.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtfofybbxw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtxswujslz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gthhyjnsvt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtrrucfjac.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtudyadfas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtngxlpqgq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtcrmoxdiv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtqbtfkhhb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtinlgjyvc.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtjwtzfdkd.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtpkonwmkj.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtvsvtpgeb.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtlsdqypcx.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtxhlnnznc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtpysnzznj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtbdepjtmc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gttsegczxr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtkxbfomko.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtsvzpzqbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtsqrwgidq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gttcnhiokh.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpujghkl.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtudtyobby.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtcpoefslp.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtcdobbzhy.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtfqibpfzs.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtbawgusvo.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtdsfeynax.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtujruhznu.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtaygfuukk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gthgvepvyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtbbyceavb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtipgqbukh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtybbdpqvh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtprmmwtub.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtwnallntg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbltyqcfc.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtlzlshthn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepootdqm.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtlwtfpazk.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtgjvjsmdl.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtzuzdvrdw.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtttpbiadj.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtodtdgfir.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtwtozhfhr.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoywipav.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtelswavgh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtzrgpypfk.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtnsycbhgs.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtdoamlzfl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtjeeyvggs.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbvkdvxz.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtfjenzuri.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtmueqljpn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtqusrfhnb.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtrvarimaf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtrhgfntrq.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtluynsqql.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtazsvkxey.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtmsbicxzm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtmxgnpktu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtvpdczufe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtuveqxbfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtitqpmpgf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtjxqndoco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtazmvvzpz.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gthfdmlhuk.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gtdidcgkyp.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdczibwr.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtllcflzzm.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtjddbgipn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftorgdzz.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtjfxfiidk.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtaywhmbst.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtaogibvrj.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtknoqzyjd.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtaemaxirs.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtvpeksxeo.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusyshlvy.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtiwjqbgvv.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtffvifozp.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gthalsgrzq.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtpgbqvjgt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gttrycyhyl.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gttuuvapyn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gthewucner.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtvoqkotqu.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtpoaevkrm.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtxlhtbsos.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gttiouqwor.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcucbbqaf.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gthvgptrte.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtewdleqkc.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtyjsigjva.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtyepevriw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtvhjalpga.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtovgodjyo.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtltqmaoii.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtglytwuwt.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtuslimcxk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtubznpdtv.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtmfuazexf.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtulnmoemv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtpvtdanfp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtqfjzcgsk.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtdowcrxfb.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtxntrjlra.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtrbsmxcqm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtqvjpuwbf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtzdxjxruh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtbrmezapu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxhkwbobc.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtpfdfehpz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtoqgtihco.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtebnmgktj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbugemiph.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwiaemee.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtlfbvcmka.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtvupdzuzb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtobhqmpvo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqvxtbjvk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfoqupij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehmwwton.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtcvklesnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtyjspmwdp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxdehdfg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtfjvbuvqs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtlqefziav.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gtxljsclqn.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtyivsagdd.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gteaihfdnr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtkjdzuwmp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtznvlalcx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtlfmtnfyn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtvqjwywjr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtpcijmimw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtrskdjmap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtpzzyotaf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtorenyigi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtcsvdpsta.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtjbiqzrxt.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtptcnkbkz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwzembwfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtaroeayfx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtvorhkutj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtyscexlir.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttffocopy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtcmzxuqpt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvfaxeqt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtnnhsinec.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtdllgaeyn.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtwheyflmi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtcrptwmjj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtjqntiadq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtsaqsqmfj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gthjptvzkk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gttmkyxijq.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gturxwyugu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtptoyrtiq.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtjsacrabl.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtpcntplms.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtreqfhfmt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtnkqhvkus.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtrrflrqrc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtdrvvgqpf.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtgrdbguky.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtvbqaerhb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gthauwomol.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtvagdctvc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtdvsrmkri.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtwldapssi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxhhcqvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gttglcjvrn.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtobkvulww.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtdajvnawz.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtkhrbejrv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtlujqgact.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtcpcncfbh.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlxytctw.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtkwvjavwk.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtounmuxkk.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtemdpcmmh.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gttjkdsjgh.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtwhlxszzn.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtewtzgagp.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtrvxzpdlj.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtnwqvblil.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtllfwnkzs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtfqceaqvp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtwnyjlmch.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtozdxgxyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gthmscqjib.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtruwhdyeb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtajjvqyhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtpcxwitsf.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtsebwloyg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtaooqqxbn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxjhclwt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtsxrwpkbz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjmuoeas.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtmfytslbu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtsyspesbx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtnfkfwprg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtlbaveoti.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtznwpbuzo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtsnmtngee.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gteknvoaqp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtusvxghby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgvobctvu.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtbapaghpf.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtmahaxjmm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtjigmmacl.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtfmljzcqv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtarzuclfc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtgwuqynnd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtejjisihj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtddnhxlfb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtjylenatp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtzspusiyt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodyejnzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtettedvke.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtdwvyeltk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthcrfsout.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gttpddwjax.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdueedqnd.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfcamiqz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtzyswules.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gttxjnvnxe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapymrzyn.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtzeiqwhro.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtqnyrdxnj.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtsnwsyfvf.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtypeumjae.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtdcrjdbtw.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtptuacbce.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtachbcdnu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtglrvwhou.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtpbmnnoqz.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtbbowozxo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtoicuqmpq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtruqsnfpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gtcfksxjrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtllyxepnh.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtmpmeheoy.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtcjtqkbym.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtlsdvozsn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtcpienvca.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtvzdtwhtv.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gthirnjsjn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtsclbhlms.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtrqchsvxp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtfqojeycu.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtutfuivzq.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gtsuepumrn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtnlleesqt.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtbgbrmmwq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gteykfjsiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtjoihziji.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtmmfziqpc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtihagqrvv.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtyuhoenej.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtuiekqoid.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtxfoncjuj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuaveugx.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtlakdddme.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtkjxrkavs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtncjsfrfg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtfqcqulby.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtnyydufvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtbftoxjlx.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gtxmfuqotg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtsmmxzpxw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtbfsmzrmu.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtwvtttjmk.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtvlmeqfox.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtnsobewkq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtfeqimxiz.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrxqjebp.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtrnqxpaoi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjzltsgqp.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtcdkujlss.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjnczsftm.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtiejtayxm.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtvitwqzcf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtecexlyiz.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtzgylbrah.html


<!-- 参考信息 -->