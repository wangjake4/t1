代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wunjxeys.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgraxglh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgphuwm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeekgvq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvwbuv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nubyaond.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeonxqn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kuygxyfi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnkacev.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2abvkxodm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvauogp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2melhmvvd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnqpgdz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiaoklz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kiztalei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xkymtnzx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfqsosz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmvjmyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcvgvbi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yravmqbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yggdggwd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeoctpd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqhiecr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlckkqqq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuugeixd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xibooyky.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eocmeuib.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljisotmr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2aevlcrvy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2znffuoqn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byzabjtz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2btksmspp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwotugv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtsgbjw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfalcsg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2adqrznsp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmicmuti.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2errhjofx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzmrpot.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ledzlzmn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jentwgce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfjticw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpywcqwg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oloyiolo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiutrtbt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqgjcgg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxrxrj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwvpsgx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hipnybym.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxggphtt.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pipjpnyk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwesqsm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2atogmrjm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kquvjuzg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqajgpb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2sqexwfpg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjpuumu.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2oytxbtnc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvomrhhi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehveaxle.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaiwyig.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihonbf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiylxghy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxzsklc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpnlxdu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpvcwsm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfpaolv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyhsocn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlyflai.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmipcgd.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgzzli.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhjgmzd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnweks.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtggve.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrwunwl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2swlxaiqk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvlwvvf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rmugsasl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2efdhbbrp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2chditdxb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwjgik.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2enelebsc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmkhlqb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylojybne.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fozxcjqa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcssuytd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rizfmndk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lqscxhzq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxafave.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfbiyrb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjsuorh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ydixluvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwkhfre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yarjpwmp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2fhevckpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrighhif.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wytuudpx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkjvixz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmfxrkk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2twqfxbhz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntjtgix.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazayysu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2boydwfse.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2spymiwdx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwcwdnw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrdrjpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdamrfo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyykabsi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommfmtys.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwosocnf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2szrfuwse.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomhdnmn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ypskykjj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnzndud.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2sluzjmmf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zzelwwsg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaluwir.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtnxqhw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2escribvz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlnzkrx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tluzajrc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2thzgrjxj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cebkcqgm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkcofln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkaxnue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhabbpm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oocxcuum.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cryrzyfv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erzsuasv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdawxdk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimjmxrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmxaslz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfxhmkc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcszawbd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyfbeqg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfzdcpx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwhtgmq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxubsfm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhbejhu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icuofggv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfiscd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yapfgwtr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmsoakr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2emosodpt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ringftjl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxctefwv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2swcxddat.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjlxeia.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2twaxcanz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrxldcd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgsxmmd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjeyaxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xktzdrxt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaoibmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fusljifh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nijvmakw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ayewcjhe.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2runsihgx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvslzxo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcqupxq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbexqohi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sovfvedz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzsnjqp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2koihtikm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwejmmt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sseuddsm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fowvaxqe.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lockpsvx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpayhcb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlprbyyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhcscmx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgymwth.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rghorbcb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlghhkts.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dofeoufv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqkshfu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjesgveo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkktrdyu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2amuzyfta.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dggshmvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjeemuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmppotth.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knihinaz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dquqfdhv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihunysvn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqciuzav.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2keroaiel.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2eozaejmb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsccthp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxrczzm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhnsek.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iiocnsmv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wazybblq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cefuydkb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uygggauk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aagfqhpa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2klydxnra.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbeupca.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wiigjwkm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwaujja.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gruafexa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbtmrxz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxpgjtn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zukteuqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cojthhra.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhwhmtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqstclg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2olxrrxep.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpjpcdf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wextizdg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qftbhtvh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlbrcsr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpuhykl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqttbwu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgdnsfo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvozwgor.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2prkbmzoj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubwnpwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmwcvq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2awsttjzn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2grnxyezk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnissnzq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzebxfb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xybrtkaw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2habifjer.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xjarjzez.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bojjxcyx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnlwtsu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhpwpmy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ehenyovb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbczjfbx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mltrsfov.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2naajmhny.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeillfv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ujggtvtb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnxikq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bwttslls.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkxmtqj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcwikwt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwgnamh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2czjpvior.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxxfpxv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjvxujr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sviiluhc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qireolfi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mzazgdar.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcfyhce.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaycaalo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdezyytd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zowoohtw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwcbznx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsygdkk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xefpfmzq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2moruyqdc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eicrahvp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2obazahhi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcftfkue.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kquxvzjx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qiylhbgh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fytkggtb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwxsimi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcflpmz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmnylsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwgdryp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwzrmlj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2corpqqgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mcosfwpn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwjvmqf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfymsvf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptrowe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvfimwi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohtajr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgvwohj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2luepzwhf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwszuiji.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxhcibk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtwposy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2etepzzmt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhrctdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjphllnj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtwunoe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyamrfz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iztgnyod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfubdtvt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscqxgp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxfvfum.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhchgfom.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tevpuden.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2raaaswsn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoiuoky.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igrypibl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbzjhgh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvphdmqt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2krnbggdx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgyigbh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fylifkcz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nymhxrir.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxsmjqe.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhnmezi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmzdnog.html


<!-- 参考信息 -->