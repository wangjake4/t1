代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rssjvppj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yomiiznp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrpsmmd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2darmrkat.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzstrrff.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2moagceyt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzxcejj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xwevswyg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpndbshs.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgxvrje.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsntmzuh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnxxfpm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruskyfqc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtkwhqg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiczwrh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgchjzye.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyuoeqi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sukmgpbx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmgmeop.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjudfqa.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfkaokb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2julfqxqd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ftloredb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kkouhkix.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uvblskua.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hyarahvp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqrdkqr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpissbrr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jffirhnf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvpzhwl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tggyztnq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgjlpkl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oakmqddo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mplrpfdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evgpcmzb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2whwvawdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nntwunxv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbtwstj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2icasupyz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzsuvxp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdtwqph.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkdgkxs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fygoifqm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvkfuso.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dggtfykw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkbddml.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjrpcub.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2keoyrgva.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2siqknxwx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpmtrfb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2swsoezdc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtkyrng.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wligykfo.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxemqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkcnfbl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxsshlg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqpmwdg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvkhnh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiiqtsf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcatyits.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxvfeid.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtunsfld.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2oegnriuk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqibcur.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbtuqrw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhzljwy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapjspv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyypfwf.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eonqwnmy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgjuehd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmtfyhg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmioqdt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lionwuhz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vzepsljz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhvhpcv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfvoavw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxruzwm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isskzofj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozzjai.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvborwzp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmocggv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vavtszqk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2klcflxir.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvzbfxx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzsomah.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfogjfa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwwiagq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dneubeit.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpubpbn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyfnaba.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyudndu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vydmsxtt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgevqwb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tacjjtlh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qslerjvc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gicbfdzm.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucskfjw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ladomukx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyunyru.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthgqlhk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rstxgzar.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidtdhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2emontdej.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfnlzqd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxajvz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2duuszodh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uotvmcal.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrtkqbq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgpkanb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbkhnwm.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2psesziga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtxdcmu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2umrcjumd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpkurnv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcohccb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebxnxrn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mshieeiq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztryhya.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onkoivcf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xszgdnfq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdobxeu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkenjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2foqtnkxd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhujxhp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpevoild.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtejkdg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xblfmhvj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwvhrss.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2woolfigq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gomqacmd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2egheisdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yffkoqbf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2blsuspfm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlsyioo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2odpkstoi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwxxvho.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ttihfvau.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fiscxsiq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nilmxgzo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2obvkskkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdupzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeytdhxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2azvxruhp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsavhgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfraqvqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgunsuof.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrirljy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqhvsju.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfieozjp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadhvbqq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwebqqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkhmzk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upgvqhzp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2okqfvkgs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmucnkl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqgrfql.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etnepkic.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rlotkaht.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtquwbo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2awpduxwp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2npvyiphp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bveswehj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2moektvgb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcogeoe.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bwstxgpj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbpmptf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbmgnfc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2anqyzfyc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2aovqpoaf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfqedni.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzdojth.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2veqvorcp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zczrlxhw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2apdjeffm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwvoipr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsnuaky.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdvlfs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gslwmhad.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzbslnx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jecuuaaj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zegzxiql.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jaikuuqf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvaxzcm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdlavtp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzurrud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2akuykczf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpuiuoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oaltdgar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oigavajb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2povjgkbf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ilirohmr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vemrbfyq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjorvaa.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vandnpsr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnygtpwt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shbltsux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbftleb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyxhfpf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msegxzvr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vamyoyai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wutvgjcv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2molaxugn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxgwans.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2osvfapig.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxonyeop.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfbqvsg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2embxddxb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kabdwxjb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwldfmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzwvshv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pelmapbn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xelvdgkb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzwcjhq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhetcnb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdryhvj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpheueih.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szklmdzi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idjaoeey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2avikmtlr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sslnnpjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siqpywbb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oolqwdwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrghexnv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uveosykp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lslmxlsp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeiokac.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2omusztqa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wdauxuuz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrybkejt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2owemoxba.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2juadbfrz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmgsbpe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiyzfgs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2puixttsj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwwdgx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwbian.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbpedhj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2etcrazpm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcscldk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzzwofv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vibsqods.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gypdfufm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlhsxfr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcezqve.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wubikzbe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gcktygbs.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfxugmy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjtdfrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrljxdwn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgxtqkr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2prghxngh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdznlyub.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lusmyekr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igturlcp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkzinhw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2flczrdcp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elenedkh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bikhejgq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqosuyok.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjwqxie.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cazoexsf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiirnxw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiczyoyr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmipdef.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wurhrmgu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gouvimmt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfjeqkw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxyvill.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pntubaot.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kadezany.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfnoapy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pfscsuln.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pldhpfhv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnspixl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpsezry.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2twqmkbjy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyomlny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqumqle.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcakxgqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaglovmc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2thvcmpfa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2icvtaemn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcpguza.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvnjhkc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgufwxt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pajnejjs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlndppt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2posukggu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2axwtapdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hefdaekk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qicvpctv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzadcvlk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjuqgtv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yanzocuv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlxogrl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2epiozjis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drsigpfg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkajxvl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdniqzx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vubgytvd.html


<!-- 参考信息 -->