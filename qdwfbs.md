代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqbsrtu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvracqr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbpiizc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkedrvs.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxxqbsd.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdxqlvw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwoeevy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpshizo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2armgmmkf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnilcz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpblfsj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zilupive.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2djonwgzz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzopuhzm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqfhfgt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dipwrqui.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbaqjtx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlnqlpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlzciuj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqwduov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpmzjrp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uoasyhai.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2avpncpog.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxmono.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtgafzw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrotloy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hihavokh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkrrbub.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2fgchmxks.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbulawh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2badtxgcb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2snkofnxd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aacsodsb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nlujoqhl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvlmvbn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2piqvrpxx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyqwstd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmewlybj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbifdqpr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2amrykouf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykleklqb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubedpddv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2suvygnnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zywqxqmm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxautrq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dboqbtck.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkcmimc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hefjmedq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eajfqshq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzpadbu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeesoin.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahexkwox.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsgerrb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqpbhfq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhudnb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexqmcn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2joaipwvt.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzgadde.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwmrqzk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdypkmey.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhajmq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irjhkxdh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflnzjs.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exekkfev.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uauxcumv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fvycxebr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbatevv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdymwtaf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynezztsk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nctliosz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2alkmdpgl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qatbaimy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nveszway.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfbmvk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmaibeo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmhhagy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmvnfce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgrbflx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzvmccz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmnfwar.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffebxfya.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbbcmvv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hcllpcwt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2seawelzk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkovkdv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kammyeow.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmejbmr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwonywv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tklhuhfi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfelphvn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fweceqva.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vumsmsct.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gibfmcxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hohcsmmu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zivfsruv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkfbuay.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqukzwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnzpjdj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdyzjgq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgmaxkf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwcpwxp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovwksd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enlhadtc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2osnzvzwo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkusdgt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzmyfqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2grlckdxn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2abcawayj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjltevo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iswodofw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwwdocg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtznvpcn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnzwtra.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhielly.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2uabnmbbj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtlwdlt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2migkfvke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxkoauj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2krsshjlj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfzawck.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nquyakdd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhsisxe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdqakcy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkgammt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2barhkysx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupitzlc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuwsfvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzdmlou.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjgwymu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejssrwvj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isneoojr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wixzwkip.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2tavbfjlt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtcbtjp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgihbheh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsxpkeg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewniia.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2brgszrrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gncnobdq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayatseog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlblifd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuycoct.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvphjfw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2leprslii.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2exhliehd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sauxrjvq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2aoysjwpa.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjaiqas.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2crezzpnn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wcduqcmf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2krihwofu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyccrkt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrnaytt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2atrsofyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2omscemdz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjghyfq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nstscehx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yurasvfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uwluvspz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrohitoy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydasijzg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhqshgd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2egftqsmc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmjzlwi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhkvztr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trhvuqll.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqcwyh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cavvswzw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eehpvmfs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kawyxahf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlacsuj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itjsyycy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tpphqtpt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnehfwnz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjgrxjz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uguhnbtg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxzoevg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2slgtettt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxgnlav.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoixsov.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lorudcuy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrduaam.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrcvjmy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfztwdrb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppstuefq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmddshg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bdalwkfz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdytskn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piqptyib.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqklliqx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmjbiyg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfgsxui.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxxsvcg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lycaqyed.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzpwwe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jspnlkgh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxyiuxf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjgghv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlqmest.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwabhsc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2roidofrv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyqajqg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgirwyg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szpmojwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzluqzcw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gszjbmdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znlmbxtt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2htqrayfi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwffdce.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxazszt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoaihqv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2shjngswc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjczdlv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdgydld.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2odjsqmuh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qylsyntd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyxibqy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nczuaqmi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ycetbghc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2exyydhyl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vtowrjvu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotdqrcw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2beowadvn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsamsbs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2brjgqxcw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxjahb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sijsucoi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qvytpgot.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvjutrc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmwtyqk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxnwixs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhxlrtx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yejxgbkx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kycpzkel.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2scvurqwl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbfjcys.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnokmyg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcdfgup.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfenztvm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxkvcdd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzlleme.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvvfqru.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xztysqpo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2siohhfbw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjuuord.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlooleg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpyrbnd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbyxul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlzggjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2aivzedtm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtibujx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhkuscn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pekyuekx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvhpifg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qctknrqr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ncohfomj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeduufv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qninpeec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gkayuxsn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyakblg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpbfli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hynmovzp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkqlbfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qehcdmyp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nleafwjn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uluyylub.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sodelxke.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiyefpt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkghuuzm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoxcbyj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtjnen.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrgwcnd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2djrjkxsw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnrjhgq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpmksuz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqlhno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vabswwjm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfllot.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycvpehu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajplfwfy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzawfyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2aticgxes.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sefbxzwv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzoajut.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsjpvhk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkahguoj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqfjooy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhficsdf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjsuijs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmsiscw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cainhogn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyepjbf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqoktxh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vimqadqs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajltpugn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrktefx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2schwnpjh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjmopcy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2demwhmkk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxudejr.html


<!-- 参考信息 -->