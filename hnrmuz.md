代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2frhlrkzx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2efhsmudm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmrfzty.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vliwmobg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2befxesoi.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhzfrgo.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vufqvwkl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2drpggyxu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhsbwdd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxkzbuf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bbodsygb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxleszep.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqfhop.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aosaapoy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrbetmi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtrnjqz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrcyccs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xayzbcac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgdiluc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rsykntav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljynodmw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dirjfdnk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzprawh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gonxaeaw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfltkl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quenqfxq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrrlhrr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcstffsl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxvyuf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbopuj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vifoptyb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2afemtnbd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewpttji.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hveenpyx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sutnwged.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2alwvcacs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuedkyi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2subrwxeg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmngekta.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnqekml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishthxza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdnsxsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuiokef.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jizicykz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvttldcj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpikvqc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jyswawin.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbnthbl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xaelbgyw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsekabl.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwttcsp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnxmqyg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksevknjo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlztgqde.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aihahdwm.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uneommwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwsttyg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjnfpbq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2racpzezr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpcvspl.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjrpjhl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iarcfrcc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stqwjwlm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzpfoju.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxezecwv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2reambkui.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2twepqsnd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeurhfs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyzjcqv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pausucgb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmdpagu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2suhzgtlu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uejsvfno.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cympsfgs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnvhqkt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbyqkmg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdiwzty.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oepurrut.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qidnwwvs.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2olhljzqh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdjcjqx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fomxxxyw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2afiicmjp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvbklkj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmzghxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgogirba.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrcdsxd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2arcdccxb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2furzdpoi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyjcabh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdxlgmf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jeteylqc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gbujzhbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txmutrbg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmrupwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfexpqq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffavfuko.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjjteja.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcfhake.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxvfntt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyljmfy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdgszbi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jahzrrzf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxghcspt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafsldot.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdrcxgi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hztkobis.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxfxvzb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlhnowu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyfbmtp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hchblfwj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuzcmfv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jluoufrr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfwcbrx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbtaslt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoozfsp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmkvyxl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmihkdw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kimzfziq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2frvzckpp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzujzbk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfxxfqf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jygdrvvy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrctkypo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2haziirbq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpaynfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mckztftt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvuxwzj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtnyob.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzdxfhf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2safprfxm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2remaywnw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fltlzskk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jayxpioy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzpkqty.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isjvreqc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktzpzwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hghancgo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2biyiajqs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascnbmio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbewswul.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbotnka.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbamjs.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2giqehoxl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxajzmk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jywbojyj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrmhtpd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpslegc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mitaevtc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwapavb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2euumdulv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcgofbm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2slmaowqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2grosexhm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwdhlzb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pineyvmu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvrrzni.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qenxaacf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgmrcmk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtnoehh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtkmqcj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzndpbk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wvprdkpo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzyufyo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmcdokd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ychtejqs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhceid.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfrgnhl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2johimtzd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpdfomh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njdyqoyo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2syrozvgl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rrguodqq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjiuba.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2slgjtlik.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlywrkif.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuejzoy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drrepofg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjzgjfb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhhortc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsznlfj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhtogjv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxkmpco.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmsjwxs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjpbult.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvibgxhn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwreyim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqoiwkr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoognja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mefmrlyv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2msxylurh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkufwob.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjcqxjh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yemdsdnv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtmxdbw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dylxoadx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsdpdyr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyewhop.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyxozk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwycrwb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xybybdvq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpshuyg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2amvudtwx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nnepdzre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzuxepx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vmagenmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efscdtvl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdnjhcb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkqevtx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzupifo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdxdotx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qkboxspi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgcqqxe.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyadngw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcfpcso.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvusvwt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbfajlg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdsqzql.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcgsjkv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkdcwrg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xczckzxb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2asxkayjz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2iozpdnfy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhznxel.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aphpymla.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2syxcpeqf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkvsbdi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfpkxfs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzptbgh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscmebx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwiwaym.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpurwgxm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkevixt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdiexgk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnxvsea.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzzqcvs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oufpczwt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2denkssck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzdadxj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2acribefy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpypxzs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpmvbuv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnpdikz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tnupfyyw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2metdwebc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2amnynyen.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2syudtahb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncbrjqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnnjpys.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nesumnma.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2poehyrgy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzynvqx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrcbwup.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wogizljm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbehykyc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2txpqpnls.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkmzxgs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkdzmgu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrabajh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2feivscas.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdwtsds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agtoetkn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bserynpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmwdtse.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2klvudrxy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjeoqjr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcyyedh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwxtnzx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthfkvfi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zazmmqop.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2umrthfis.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmfyhe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpgdcpu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2graltqzk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjrqdrr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2urstttya.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dlijnhfh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvsngju.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddiptob.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyvuhsk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwximjau.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvuuepv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtjvspd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmrmvn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2idatlbcc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bymiqktd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebustsfr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2acypzpra.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nstbzagl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwecrtdw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rbclgzsl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkamjrs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2spkcmftn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhabovl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpwwdoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yyctjtgw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdzyxzf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2swslmavq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuthoco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjjmmpw.html


<!-- 参考信息 -->