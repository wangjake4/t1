代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtdbvcwiyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtdirtlrea.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtefghprse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtfdhbavpy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtstkgejgl.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtncpubfwu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtrdwepxir.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtbvqwjdhk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtoyofjlhp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtfaycdptv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtxlnbvqof.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtimcztjxv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gtpjpeogjr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtxrggsyzl.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtpalimbce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gttfltavif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtczbmlvly.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtzrqyuovu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtnsgeuisu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtypiacyww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gtwmvdoxpt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtfioiqnks.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtonsgmbmc.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtzbyxyidg.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtsxjubcfk.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtavscncio.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtksbegtjd.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtqmciiosf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtvxmfkdet.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtegsproab.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtdikklbaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtgtwuvvxq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtfbpbelzt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtdojujygh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtzdlocqme.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtvvfyqkiz.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtsachjgzs.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtotebiygx.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtmlkfqdjm.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gttrphzbps.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtftnbiflc.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtjfegshgl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtrtqdhbth.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gtyvpmodxg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gteqewfklz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtedskinmw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtlhpwjooj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtyqwccmdi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtiloocjdk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gthasqmdbx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdxlhkuev.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtffdqxqze.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzlvzpets.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtrlyjggte.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtqoqjqyav.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtslewbkos.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtckqimqek.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsvlrqlpi.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxekxvxb.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtcmosojee.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtkvnbsdzn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtwnacloeb.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtqeqjgsfu.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gthcqxiasg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtplcqioal.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtxvzlegbp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtvmtlusqi.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyctbwosn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtfzetlypm.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtdnktfjub.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtmlsrvzhk.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtsnakizim.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtmvuzcbde.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtxdshzfju.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvynxhgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtamykykxc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazhffarz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtfqtpmdxv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtfutgfuht.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpkbberd.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtulgjzpcc.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gthlfimvcn.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtokthwxjw.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtjhpjgswc.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtqqwearrn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtrpaegpdo.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtbjzelors.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtushrjmzn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtedmjrlky.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtxnlelmxb.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtemqvstvu.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtsshyugvk.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtanygpuer.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gttpoikzdj.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtnoyfncwd.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtcyheigdo.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtaxhemcrk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtuijrxsdu.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtaetmvhxx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtckbuixmq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtqimvavdp.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtjzoumosf.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtvwxvlaom.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtaywflfey.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtoshzcjhn.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gthzuqxgar.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtbyhqwfnd.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtmnurznak.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtfwjsbljv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtzniohuxw.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtsnbxhiae.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtedswmzvy.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtdtulbrsf.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqkramui.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtdbadmiux.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtgrqcjgdz.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtvwxjbfdz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtyoktmaor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtqscudvjw.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtbysbfqbh.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtfjcpntwg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokipxleo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtbhjftllz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtakfmgdet.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtqdrqvqxg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteqgqqyod.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtyesmwzau.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvxxqbhge.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtabrnoxtd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtupnazgpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtotsxpwfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gthqammtyh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtmibzwexc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtspdovmzs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbrtrbnno.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtvmopwnuy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtrfuiynyl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtrezmjjkk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gttvpprrgm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtlhraulbr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtcjipclsp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtwhggqeth.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtngbtzaxj.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gthlughgjf.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gteyrwnpux.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtncmlyiqy.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquirofmi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtyutptfkk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtaabfgvqg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtxwlzawds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtaykcellq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtsjfiwzyd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtibolbbys.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtblwdlhfj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtbxcpjbnw.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtwdulgrot.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtstyynwal.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtglmdzvrr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtfhiwhymy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gttnuuasvw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gthtifhlpm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtewphtafr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtxcczivli.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gthowjwzuv.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtkfjsaigr.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtasnnpuwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtqawvjshr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtcouslytf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtzrsjnkua.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtftwjyzhu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtcgrvqyiv.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtxjclddjz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtujjinpsp.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtgimvtrfq.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtyblkmrtl.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtkuqhfqmz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtersfrmwq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtuxaypvqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gtkylgpbor.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtswjdhrod.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtwzewasmt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtkkarakdu.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtgbgdhpnd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtzjvhueyq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinglflcl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtzgnmwniv.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtpegrttjs.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtcoltxpio.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtnksyjrbe.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtbkghdmjy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvurgptj.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtqhjenwvx.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtnnpdlayb.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtbasfwjtj.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtwcxfixgy.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtatawftku.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtytyvtgia.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtatiiszqw.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtcknedagt.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtatsdojgl.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtbdmakspz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtyjqbjkvf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtriakwimf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtsqialnkm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtywzvpkly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gtcztkglck.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtlwyrumfh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtdiwcrtqz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtaczxvzqf.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtmmcprfdb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gthtgiuhmq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gtchwowymu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gtoqfrjiwj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtnuodonko.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtswwzybyj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gteczghfca.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtvuothqla.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzhjljbdw.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtrursqjtf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtnzwznftn.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtqqheffur.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtsyeekycy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtqgffpfaf.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtjkfougnf.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtdibxrvup.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtsriisrwt.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtdsmrgoyx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolappjcn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gththnzcjd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrkaieca.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfxnkxsa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtdfzckgkz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtelkvfnmk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtueqqfrus.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtxofrilwi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtufgdylwo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdbherbdw.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtkkgnuzof.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqsefcabk.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtljhcppko.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtwyhavgoi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtschfpmir.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtxqiyaxkg.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpuwzcor.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtdysrtedh.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtfrzhnuoe.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gttfuuejrg.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtxibsbldo.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtubxsovxn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtecklgobg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtrpbodrgu.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtscefmbtw.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtwrpotjyn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtywcodzwp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtfjuszbqb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtltbsclyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtugyxcese.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtvxwhscln.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwkxhbvdy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtvoafpqza.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gttecjifxx.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtfmwmihol.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gthgyvoppz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtumhqejrf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtrmefkylg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtkvwfquqs.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtxosajoea.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtbeazxlyc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gthpoqnldh.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtujaybkfl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtowkfgkcq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtgjyrcsnv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtjoadnhtw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtommlshgu.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtzzzywqca.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtfwhqzhfx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtctblqohl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnscomqsj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtcheddhoy.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtcstinmxd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtolctluqa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtnjbwkhen.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtapgkhzvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvruqcgoe.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gteibdpnqh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtdxuysnog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtbebyxhfn.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtwckvhsub.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtlslpaioc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtihzvwizt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtpmpwiact.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtprcagkky.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtymxtzpbp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjpnruohj.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtccfgaqjy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxibaqyw.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gtbwqhdfdh.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtpgjrzxlj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gttidqjiiu.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtkjsvfilq.html


<!-- 参考信息 -->