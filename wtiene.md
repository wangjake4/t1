代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2csfrocei.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjuzdam.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvmczdv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2iquoaewa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgvalww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbraxtcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnapzmd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iyslegdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2envohptl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyazbeop.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kzycsqwm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwbocpi.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwunae.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijfztyw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2byaoxrrk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaczqef.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2glezzlto.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2oimcuxvk.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkoclnd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqhequx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhqxjvo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcncghs.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tjovaikh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2novkodqm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhwtqho.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2olleicmq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxxkzi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiemiii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkololm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zflnyohc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmhvucy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptjhqa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjgwnst.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolybki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qpromevu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkdxnty.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ialwpgxt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2naapawpa.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2shrnfncl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzoajl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaebzuyp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2coqsbcwb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnxxzia.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvcejtm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qijvskjy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfwfqeg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgjdsqk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhmplb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrdmihn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgutoyfd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqsgvfv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjktzdqa.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpnuxnh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgfhcig.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2txlfdomw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skfctcec.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2krqpudfo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jswiplzk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2chcywxrq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcwmieh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvfuuiz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjsorpd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxfdslm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jquuxvuj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcsqkvy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlejoyf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzkmclz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2znitmdpg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eavgquzg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqxvmyg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xniiaapr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxnligy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzxtjzs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcijgjrw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjornydy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fecqyrsq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zvstxeea.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltewegem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kivuhlsn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gngqylgz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbajaff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjppnbfk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiglagr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfootdyx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvgsyk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsrdijq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexopnpx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtyjkdl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkarvkpk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzrqbyi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhjuxhv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tddghjba.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjbejhc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihanznns.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fktpobhb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgptlee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wktkvmnw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhuyedb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjpwwhl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxssvgaq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqyeaua.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnwofws.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjftlzip.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2foarattn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2golatpbu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2emmogeej.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bolbiwaf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qnttrmfa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2euuxqgie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqmhdvu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vockdseo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyquplfl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgfvuvx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielzrtay.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxjhpow.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2erqhgtoy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkcfmlh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzukafiy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkpxtos.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yanttbwj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlcocpu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyubvii.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiidhxme.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haisgxmf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaewmltz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgukiucy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyvnvzq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2elnnwath.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrsjaoj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiazadm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvrqxds.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2muorrwik.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2otzfscqs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmmrct.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2orrnioqb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpqyyxp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2feijftxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mkltvimm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2arqhilfc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2layiuytp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2psslbnoo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxokcose.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oufzsafp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnbdgb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxyrcym.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wcewiosa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dcomnzpq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pddcfnju.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmcptbv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxdkbij.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2twfyoomw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxomdws.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiwlaoj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqvqjwi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2eurvoszt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tklibvfq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcnbxhu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhijxxd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xynkdefl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkiuful.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhjxtgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxnrlds.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzivmkx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2umfjdewo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqansein.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xguxspnm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuabngwq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mocytoeo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdattfs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpaojjf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnxaryk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2crpxgtsm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafzzgwo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfpahvz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcumoei.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdtkxdi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vulsnzbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkfphup.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nirockjr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnehcit.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tddtrefx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iixyyrvk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmcgcuq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrlkdad.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2esrhafub.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwulouag.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbotmgr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eucnikgx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nsekosnq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxahaxa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddkcrmh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwfgcmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjanuzbd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mankghrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkmgego.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcbgfto.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeywshn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcfwjut.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cikrqqxl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaebynw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnonxlz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfssnbyc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbilcilg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qltpwrih.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2guavsdss.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhonjoc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiyribw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2meokijvv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2isofhgqp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdpqivi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2stfphigu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jvojhmzm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2unrbtxef.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrgqgwe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmemhto.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mksymwau.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ylswznts.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2euwpcecu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmydiet.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyyxsrc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbchjofd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqojhsk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjjgyh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnequwz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2eukgkaof.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfdgve.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpmxmls.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rewqolzp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2flohjryd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqznfab.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byzcosjd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aubncnpn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhixyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wpquhvsw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbmqixr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yongpmto.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfihjoh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2oblmzhea.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzywbwo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkjvfwp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjulpbp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2czxwemml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzglhwoc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmircsx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2urfhdgeh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2geqvvnga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjsjaar.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhkhowz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxylwuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qktstzqq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjkurwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbizgc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2acbwpmyr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2awktbcms.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdiysvi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2enejpazt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2msekvehc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqawroe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hysaqlnj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmamkvw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaeuxik.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2beeckotc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxypfxfl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vttzippe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwofieo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vibmvlkf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2udotjhxp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxdmgmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejbtifu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcczqsl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ekorvsov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tljwbjjy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaglhoio.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rophcpdo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpfuwuc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxulcxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2evigbyjg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephtxcuc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawrfev.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcxmjhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wleftrkr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmnrgka.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhxnli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpntftf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpwzovj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgffmej.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcszdgi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2amqunwed.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tcepmmwr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uytizhvb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnufcxt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qredaiaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnckgwo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhvxjct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onexgxfh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhwztmk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zypyctdo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjrjayo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuwtlgd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2untnrghq.html


<!-- 参考信息 -->