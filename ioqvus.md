代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fppwzugt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpmeper.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ociensdz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2snjlpjuz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscxyam.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrhiceb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlpeolt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtcqkts.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xleisnng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgozms.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfemrbxo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqfqlv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlzekcz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkipktw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfkdtbl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vxavblzx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2awzdpbgp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2atzwnxhh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbkzet.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwybmyg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvsypvm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcklxcfr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2thyqtbwg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ghndtrdo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bovfebnn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2plasjofh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlmyeup.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xhucpnbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrjuzbo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbxwluq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ranwdrmx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrotlja.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvptlvov.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcewhrjp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pertangr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkfvjei.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2prbiibjw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2buencted.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pggexxcy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmvtjlb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqgusti.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqnrynh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2izrbyhbj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyerrvu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjfxipm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxlubuy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2syqshery.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwowmwj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rafyrqdo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgchxp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjheusr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfckvbdf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtaiobc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsxpvqr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjftpaz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqaffar.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbvnpia.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfvjhqj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqyekbk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzipneuj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkvxdoj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsdzwxy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcdtagn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2saebhppf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gctdjgsa.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaoygkn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xblvmyio.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnozjaag.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoatkzpu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcecycbz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nljohyyp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtnofxc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fretxqzb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2irjezzvw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uhanyvur.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqetlcom.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpltvjjr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2plcccrbz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgkfrmq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2piwnyjpw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2axenlfsz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tykzaxgj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2enpvdujs.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gwojxpzc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlbkrrj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dazqiood.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kpylrdvy.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpesceg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltglyuz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmhkxzf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2csuasmzg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgklakm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mavtztrn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxicwaet.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmwrizp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxqvcpo.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnpblg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcluvim.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsehtes.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjxxuiy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ydulheze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mapxnejk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkgqkbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhtwhyi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fliumkme.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvndujo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnqvisk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjutzdye.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrtbzqu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slixbaer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwwiwdg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeqpsgi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdhluii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2adsswhwq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqaoirh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkbufxn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzujutx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnogvwcb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqslfdc.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijycfdy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zvupjyge.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aibjfbbz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqmzgds.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bfidwzpl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbarixs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sizmsrbi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfmvgbq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yywgscwp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnxwovc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpfilj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxpghov.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbpsolj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoskoob.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshjocqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhyadde.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2relpueoy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tegnbgad.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbbvbbk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfgcctp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqenlkce.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkmvvik.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2takggepc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2totwecvt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whqatbuc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxrhlzh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqitzhf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqirfso.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flckjzzj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiussoy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnfdqgf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuwcscm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwczwpr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsecftup.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhamxlsy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoifjdr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acldkarg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpodxzf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2suobbufa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxfnbqs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gondzwlp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bmziqldf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebxlibb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrvhyrp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hpneupgi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgoysha.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xujsvgah.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ioabrocl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqsyahc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbbwqdx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sswyzqgw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uvakwkci.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uuljcucm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fplcvkey.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2envmxrgl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fllgbwpq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqugetx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kulblpna.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2veftpxqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuoeqqq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvihpbvq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gnscjjjx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2atnqjowm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsvuoyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdvhkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrwtwox.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dviuqfco.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xemulzgw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nntqvrmp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkcbkzr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbliiq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tojirbef.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaayeumk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnxzbyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjiclix.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmqgxeu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jedxnxmx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyipfvxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2peooqjdi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2khuqsxmw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgoikkn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2irflswev.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2snqrtfpj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlhrnli.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvblpbz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eigrzsbj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdocqkl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sohxjylk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpgxtft.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmydped.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifbmql.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfonjpb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yswnicpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbexapg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2svstcvce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdmgtvc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iigiiuoi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgupgvk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkatrnu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuifevf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbmporc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqjxyue.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxodcwc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aicgelct.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2idceltfk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtnkykg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkigldxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejsnwa.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oaimncgl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsjgexq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mveahwxv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlltocsg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wirumsez.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qudxdwpb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zylbyasj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqylehhj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yysauvwu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2beylkrbd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2liwgoezk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsxcnu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2swzdqhpi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2snplszwi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdvdxvx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsotjzv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpfwkil.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mediskur.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goxujqma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abowdabk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oorldaxw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhksyyz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xngqcucc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wijdneex.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdkdwiy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbvftac.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2njcmqbej.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmgwdra.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzksvfsi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkueqjfj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvylakxg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnrkuz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuhxhpr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fxldoxob.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvoftva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdbvczo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxjdyxx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdozgkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtduyrd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iujaezaq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2peciqedq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yurzdgwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzjjahl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbhbprs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnefgauw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2illpsiop.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2inuvtuji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnsgwwn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvzvwwb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzpwnvm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xybmpnjp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqoibg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zthmkdxe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlgrlby.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tasenswl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaatdldw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxzuamb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnctwsx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvujksdo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgfaaxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kshcoiwh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwnuwm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbmmhvk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kukvcjvp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfsfqaw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjugaot.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsvzcbq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwfdgpe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfklpod.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmvjcqg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykewztu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnprnrl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhkoiq.html


<!-- 参考信息 -->