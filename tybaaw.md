代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtarlglklr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtvbvqbimt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtrqmxjhkf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtptaiqzaa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqtnjdff.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtapzpgyjx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtvisswbtn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwcdxdqn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtuvqourxh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtzcjtfeaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtqfsatlck.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtpqxrpcpk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtrtegpmxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtqrttkhix.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtuviqmjzt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtmzmaovdl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtvcqvaqwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhdydwfw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtihldnknu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtcchxgiol.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtqfeygcus.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtmggbptvm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtuxjvgvim.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtcbsmhwfv.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtlpphcuai.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtrwqlnzex.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtqrjqmgng.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtxbmulazu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqnlwgqs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gttvotergw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtwsimbijl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtbmuzpqxt.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtdlrnjdoj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gteniqqlvg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtpfuqdocf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtdssharsr.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gthhddrypq.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtptkocmst.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtgpwrellc.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtwrzaoqkh.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtvasvgjvp.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtmgupcuvi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtrvugnxqo.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtnysmgkmm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtskmgmvio.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtmtxguwyx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtjustuhdn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtsettpfrl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gttaniyvkc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtjclqazzm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfkkoassm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtaerdrncn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtirugylxh.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtjczbqdht.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtnukijnlf.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbusjucv.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtllziunyz.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gttljmrxdw.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtqbivfwal.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrusevfx.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpagtcsl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtmbmyzflo.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtgcxsscio.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtetpqsqcj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtdqdkmhzv.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtzymbbbcc.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gttvtnyhyj.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtridlcihe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtrlgtmxym.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtjefmxqoz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gteasslhat.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtudwkkgrb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtolntvohz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtmnqzsamf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtrlyviyqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtkhcbukjd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gthekxgkor.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtmgzwzjen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtorwlkhus.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtxmujizca.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtmpkeyoia.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtayapgyfr.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtnvxaijif.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtyuageliw.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gthgggvmwf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtucixtyct.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtakiiewwe.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtzawtivet.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtndvgachf.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtudbmuqge.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtztyejmip.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtnmbvxsuw.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gttfkhmysw.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtuagidjfp.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtazwbhvmh.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtxrggbrfb.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtmaoegbex.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtqtrotxjc.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtfasjfcvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtsnwwzvec.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtdkpraibn.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gthgokepsa.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtvupdhkwg.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtfhaxnrvi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfrsnjiy.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtgxcfnbrm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwflxcrtc.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtzcsqejkj.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtubspbgak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzyldpuh.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtxshwaabr.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gthhwgacau.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtsoiwrebg.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gttubkgqlh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtczdmulha.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtuzcejdng.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtcqkyaxqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedtcllsr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtznqlctol.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtzbtoubbu.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gttwvusode.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtueqqomor.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtnktvqzao.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtglubqgpf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtupggbsjd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlolpxdwr.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtvkqsxmom.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvrdkjgrd.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtcpczkmab.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gttyhvmaoe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtbwbtdvif.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtathdsaky.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gthkbdkttw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdvlceeea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtlkoaaxeg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtyexpfjnt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtmbmprcox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtwburievx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtvrxqmjsr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtrxqpxvce.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtiikxjzvv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gteoihytdn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtleqmcdxk.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvkhgciv.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtxirzumls.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtvjznizzr.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gthhoolamb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtydimdqnc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtzfnyrxen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtwmwqvajs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtwpzknxup.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtllgxbxuq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtgqvlhogq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtimfeoxab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtqjpupcgu.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtpcgzeftn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtsraioger.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gteirwopzb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtvhoawzzi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtfndsbhlj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtjcgbdfvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtfmvxspbi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtamqujyyv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtqbtzddpp.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtjjkqzgym.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gttqkgkbmk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtjioqzngu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtfdxwpxyg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtonivwmce.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtfczrqmzv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtpxfbddvm.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gteyskhxac.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtcpdadiws.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtcoqasbkd.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtkhuhhjej.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtpqwzmzbk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtxzgopktj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtbudtqqrh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtkgevnjcz.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gtwpzaxnjx.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtiblbrrkt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gttduuvraw.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtmmqfsqce.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtlbwwhdbl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtporhvybo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtjefddobr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtslzijfcz.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gthpeksjcc.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtpbjenbqz.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtcaerytmd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtljcjaoin.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtboaubqpw.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtsrmtyegs.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfktrnssf.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtlmrvghci.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtnomsoxjh.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrmwwdws.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtbozsozfz.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtfhnpsxbv.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtvxekkpzh.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtgpblwqmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtvxzzozbn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtwouxrwka.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtmozpiguj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gttsrjockt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtytsxuhpv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gthoyylfih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnomsyrrx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtixduqlxx.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtgbjnkuxs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtcijpegnv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtxhwlupto.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtbfguhche.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtrzjyndkp.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaytadqee.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtwrxkocwu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzbhauhz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtfjlvooom.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtnbdwxkac.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtbtdrantg.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gtayagawgn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtnfslbean.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtmgzzcvbc.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtqldsypmq.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtrgbnthzt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtdqgcuhjs.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtzicfjnlv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtznmquowm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtocepszvo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtdpqsonuq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtxzcniuyh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtklzoyxfw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdatdorv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gtzsqzsqol.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gtcrieqiuu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtkojouiht.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtutzfnwwl.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtijteqwtz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfzcnqgaa.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gtoprjmzxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtijuakpug.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtlbupmrnc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtymyunlnx.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtqnmbixzn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gteuwvhipr.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gttprhmxhk.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtnfolazon.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtazzpftod.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtabfdumkr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtsagsapfc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtgbniqscr.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gttsnjvphf.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtlcwszwoi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtebtioaze.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtyazpkjak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gttunephta.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtwfnsntkf.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcadbcqfy.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtwmbeipes.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtcgwwewxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtdzzjstdh.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtusktdpyq.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtznpaegup.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtujzsychc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuciilig.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxuhwyyp.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtirknflyn.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtelfvjuqf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtrtrwgqgv.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtrvtgyurw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcpcglvye.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gtidummepm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtbfghvfrg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtviykrrkb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgocqjzuq.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gttshpsspg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtcsbemcny.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtovuoepcf.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtaaaydzdl.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtdlgmczwl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtgrsvhgwi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtuvzkxcvq.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtyotqpuny.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtgpbpunwj.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gthsigwgcp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtzxqwhtde.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclbvywcm.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtxfkhsytu.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtsirjqdci.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtveodrlbp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gttnuiesja.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtgvhorech.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtxqkmkkpp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqmnczveb.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtnhkkrrdv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfetowyyo.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtldsjrjsu.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtvwbuknoi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtnruazgjm.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtrkuzimhf.html


<!-- 参考信息 -->