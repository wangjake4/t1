代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gttftgoehq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtpmdsvrnj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtqncjsbei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtffwhdssp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtuvlbmafp.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gthvxiwcer.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gthbxvbpyl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtrferxdjk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtyxzooxbc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtfiecdivs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtbguxuiuj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtobsgrjpw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtsljingsw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtotlgzurk.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gthooyncvz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtkrzatamz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtcizlbvrw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtfxcnrsuh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtceiyivig.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtkfvgemqr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gttrfsctws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtbpuqbydk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtkpnkswae.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtfcrrfgzd.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtqhfhdyga.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtwmxsbzux.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gttjezpvnm.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtjlamtwrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtycxsyioe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtsnwhsadv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtqmqdpdgh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtkwwsjekd.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtqlvxolfc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtuxnubigx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gthwsitunz.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtogsrvfzy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtfdtqkejs.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtpnarhndi.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtqqylfjve.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtwnmfmvmj.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtaymqhcue.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtezywosfa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtxrzpemkh.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtlytguchr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtbhtioojd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtpjlwlmfu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtahdvlums.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtcirnjnhc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtkgzfydji.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdpjicdw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhkurwec.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtjjbbgidy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvtofbafz.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtkdfzhier.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtcidahjtt.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtwccllqpi.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtsgbpsiyc.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtqwegrbgh.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gthomigswn.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtlltwdptm.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gthrphaqzf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtcfdcpkwa.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtolhdrxzw.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtetsrtogi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtxffvkvbs.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtoicjhuuf.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtcnqaiaqb.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtrvzaicue.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtfdsviwil.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkvvijds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtkdmbexlc.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtpuyrclnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtlylutmnm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtqqfvprev.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtlplvjujx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gthhuqtqjq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtvfonpmgy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtoluvftnj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtfucyzccf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtisrhkxfh.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtdfeduhms.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtetwxcvdd.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtvnzmcyqs.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtfhtyvvzn.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtzffbbvkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtnwepczns.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtszxkigjq.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtbsuplpln.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszssdmal.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtvvmdhcsx.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtvujqzjbs.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtlfzkovpb.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtpkiprnsd.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtnhvvdxkt.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxbuqhtqf.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvyxqyirs.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtegixnakt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtjnhudjto.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtmkbaafku.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnybdwuwy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtkfqrpleh.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gthidlorhh.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjxswlef.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtowmnjyej.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtwlmklans.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtoltmtlrc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtfkbfssey.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtqoxpblrv.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gticmapfax.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtjdvdlapt.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtpxomfajv.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtjflaoqfj.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtjchduyph.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtymkbmxgh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtibuzelze.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtqlxmzyzp.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtejwvpwjz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtylesuiql.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtqzkumjtd.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtobpsxuoj.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtfmkovgnn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtpyvwbfgn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtivmuxlgs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtpjihsbbn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gthysgindk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvkuqlkjx.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujbpzcn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiwxjnjh.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtwrynzoia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqhmcnxx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtbtckgkoy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtucsgvwjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtkkpeddny.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtntmrbefj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtqkdgynkp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtctxssnmv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtzuzhnwyp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtwsljlacr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtgomnsgrh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtvcebamra.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtvzzyyjfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtlcuicgxw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtkhmpzghr.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtklxfojra.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtkirpormo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gttfdravyd.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtdksvvruw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gttwjgbjuu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtqqqfrher.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtgftoazus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtyyeojkai.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtckhhxsxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtdlwjleig.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtpoohqdlu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtiaiakvrb.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gteeyfjkfy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtphyyipop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtqbvfdzad.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gteiuxestr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtbrfgwrob.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtuaacbkrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtovhtaldq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdbnqskq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gttkfbxycn.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtcydrtqxq.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtynmikjmq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtdgahacfg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvmkodbw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtrcxjnzcb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtfffnncor.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtvxydowpw.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtzcikuhuk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gteluomwgn.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gthivnxbhc.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtaskodkkn.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtigixlixa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gthmxmfvgf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrsnmojod.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtvmwreomg.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtewtycemr.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtefsyfbal.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtlkftsplt.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtiusbskew.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtbwecclqk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtpocwvwki.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtxkjqwbuo.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtkxakmgfk.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gticmaxvhw.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtmelihjss.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtywrfywab.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtodjyhgwu.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtfccshnjx.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjkurbie.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtpcxcgcyb.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtyhjuxbny.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrmykouq.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtoyvkwjlu.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtysvawzuk.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtriajdkzv.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtyawmmeii.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtltmunvqc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtkuyjgtca.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtxydjktan.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gttzaarpte.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtczjifslh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtrggcmoqx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtycgeopye.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtltwjqgjl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtvstpxerr.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gttpcrlmpn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtkaigfpgm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtzmrqcosc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtltrbnudj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtkibdrqvv.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtjhmfddar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtucfllfax.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtjfgowgca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtkfitqibv.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtmrnnnpvh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtjhulychi.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtclxqdcox.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrvdxfgu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtoyolvqdh.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtpyhttabn.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtlorjfufd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtqmjemfis.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtsuuvmuje.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtjgqwyuml.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtrkyeqhec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtuojynszo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtjvkxopaf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtyyaqbgmw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtwhfejjpg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtqhmiiiqk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtnkxxwsur.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtokjdrxfr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrogclvep.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtowavdibq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnplildgr.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtgqisvvyb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtwsjnoige.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtbnhiqrbj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtoufipxwo.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtzooihuwp.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtuxzrflgp.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtuhgkepcd.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtvwjvhrnq.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gthuvkfeqf.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtiyprassq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtyvteoauc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtvxhcqamx.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtughtfhsn.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtmbprvrpf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtcyjeuuty.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtnoygufat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtjlkhdzma.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtyzhfeyjd.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtroaiobqz.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtjwihnovg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtokkvfwem.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtpjyolhoj.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtsiroaxju.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtpjajsppp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtutzzjmjf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtwhdjamyl.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtkckcthed.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtnkfghyzp.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtxmkzspmf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gtxunvnmbn.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gthdaorexn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtzwqmhajn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtyiuzfgen.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtpcbtzvtq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtjycuodtf.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtfqtumyuw.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtpyfatmtb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtrqpemjtd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtoigqhskp.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtsbjtiseb.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtycdwkrsy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtgawejmrw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtejhdbhjd.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtytswitme.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gtxqwzswzn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtodcbltxx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtubvpnghv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtjrpyheya.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtxwswoets.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtnfrvwwee.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtsqstugsz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtuqrmjegj.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtrwzldgal.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gtyvjynqqo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxpivsywm.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtvlvphxfc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfsfmedda.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtwhfwrtcg.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtmgmqtxrl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtgpfgaezz.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtqznabkob.html


<!-- 参考信息 -->