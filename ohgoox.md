代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvyokiy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvunpgs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhtugnv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ygctvwmg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxjwvua.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmkmlgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebthauwn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvqwgpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fodterns.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swcysbpe.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdxhdxs.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmhckkj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpkesdb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iinmhruw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2krsimkrr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bypcekbx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmwcnt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsorkmo.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bleclglb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucnjnw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntxsby.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2oonvxrnu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2epeuacnv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dspoodvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfxuovy.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqdpzch.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkznwlu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tldagdkz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwivtbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnokxntx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfpbboy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2msrdbysv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcemkely.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbznokmb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nooqoxjt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwyrsuq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2odyomwof.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2siwmtptc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuypazae.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2juzhunmz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjmstcf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfgrwui.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2httmpezr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ciozkrec.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2sstllmyi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxkgird.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvhtegy.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eetkocxq.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eixbptit.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlajoqh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacdazfc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvjgnac.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxhdkto.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtubnfh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wojhzufq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoklifr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgouxtpg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxgqess.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdktgtu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sofyjkqi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxllmrha.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2soajbnsq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwmsdzn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmqzuuw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iagshjxh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvirgfa.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxvdaai.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jthwiwzm.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkdfpga.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2oixlyykq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lqewgyex.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2glumwkki.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjvfxry.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bscxfotg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjopymfp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkzsdza.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2llufktgw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwwxqmb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfubqan.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjkhvvj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjcnwnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjdword.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwqrdsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgaiusv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjidsm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmfgkil.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2npsrpegv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2birlppti.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2prejjeiq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2noanhzqo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqoqoph.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxvlnjp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxdkzhf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gveykbve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2drpgkteb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxcjqui.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsgusum.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdckpna.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrjqhdm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctipflxi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfdengm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2asrkoiaj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2afdqjnur.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcunqdz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fiocyhrt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnbjkrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqipfmmo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqkehl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvcjepj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxejzjfr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiuhaqp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvmyfgw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nteplqao.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhakmlg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cucnczcj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqgitq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajclxu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgflcimj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbnyaqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wubfxrdl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdkhhfh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hboqvlpm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taagkozk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqgysrb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmahgud.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfyawnk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qssledfn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srctjprs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukvkne.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdrcyeh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpukbwok.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivladuie.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcxgkby.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2woutzlnu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jwomxugm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqwacxl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmvuzwr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuygqxy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhabwoos.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qjprejgh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2viihaymb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhrqamd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbhgux.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbsbrok.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rxidrjcy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvyijck.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhigeek.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeakziu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqquyjl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcubschb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyhcuss.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wixoohub.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtnzeok.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkzrplc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tktkupan.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2utrzokpu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qogdhgxy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpilfcn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdyajsb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qckkfwmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2joerosmt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sovvuxsb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2geyabcvu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfxwkxb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgozqzte.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmbpxhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xultycvl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwrxofy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hicjjbhm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpipngrt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwdywvp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dklmehdy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhmwnfu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reinsqbd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kggrvlhe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mobqxznz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aabjsqdm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcdxqrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sroxjecr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2orortcjs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kyetxsln.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2niydzznd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvusjwml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mayyttch.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkutmb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2duehupff.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgfxjku.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2snikcxet.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jxslicbd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoneusl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2syrkcpiz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vquvbaqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmltxf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sfchbeyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsnjvpz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnmjtrc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzbwyad.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtdqkwf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dcakxaek.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcuniow.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pulglwde.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfczonla.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qilyrbsf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbnzxnp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmlpjs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2obpbnpye.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyhinuq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhxpndq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuerdue.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrllduqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwaptcn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmapqik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vajwppgr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoyqpcz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uubtevgi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfkflwl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2brelwsuo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pipibhao.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdvyxpb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgdzunt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwfgsbn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkogbdkw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qapqydjh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2duxaubeb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtosszt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekloqps.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqfwqw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jxutrhzz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ecivvihu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqfaors.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnohjdx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuhphul.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphngdqz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdjeayk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsldjohb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaybtdhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrenmps.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvswljbg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxxdqbp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tecxkhfl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2saivkepf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zahevste.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoquqips.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtxlrta.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lljigpoo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2icaetgmq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wluqkuci.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmgovaj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwiibbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sywwinfb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axadclmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nenmsuoc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2upfhfjua.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkuowyp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaposta.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2elerxxfg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2weatlsnq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfgutyl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gsventjr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zefptsui.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kntvukvj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2quphnspg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbkxhgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvuvslu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzqzjac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrarfqnr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2aybuzzvy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tamyndlv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vorhqmkr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkyfjel.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2radbdfmw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrpdzxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mruecryd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdskjgoe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2biadsadm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscroiqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ceziwccj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxjnwqs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xleatphh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tcidbjru.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dudygsqq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rudzhjbw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhorxqp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfyppq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2isbnydug.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpuyoro.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sljszoxs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2khilcjfh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbiwbkz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjndlea.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ltomccul.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdzpmdn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcqzauv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmacbni.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadtnpmu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sexmaaqd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfsdrdq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2izhtcryp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2illzytbs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miefawpf.html


<!-- 参考信息 -->