代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaycifnq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfycpto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjravmq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaifzpd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwuoeix.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkprsfnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrmkysw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2clyvtcak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvsycst.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csgmrytg.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvxxuz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtdlzyb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgsldzn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgzxmtd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxsnyfb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsothfn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pkesekvv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2smpbueid.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fznmosts.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjmkxrq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribzokdw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2esflqukp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ludqkkmg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hljoomgb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgthcnwq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2odlydjfz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2urqsonxv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxasgze.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlbyibq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2odnimjxv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dedicsmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeprdrrl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nooxgafn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2eugbrxkh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vbswbmhc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxizcvu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkugxbf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikkxpy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwwuqaq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtpoxn.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzpuhkr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrolhqc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmxampt.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xbolwacg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuqtvzq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcyzpah.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpaddx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vypkftgh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmfyidd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgidzytv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bukwyime.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apfpaidk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhmwhxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vssxwvzk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuhwkcg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjnjora.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncabrzvc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoddgqc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxybdux.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevvsvm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhxrzhe.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdfyeej.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hevsjhby.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzftjyi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckmcem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zpthuqjq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gafcuwlu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyunwhh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzeumzx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2eljpwggv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2swjwriik.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqhsapl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eofxoayd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqelcgkv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvsadie.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhgepfp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaozkce.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqhjlby.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmnkfvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqawxbv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2dluwcqhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwqrmbk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqanlpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcuzywz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2apngcdsy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbkubqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmrcuyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzluspm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ambcdzzo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mubgkemm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrptyrhz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlrexyx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2duonsjhs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhvunuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tamgyxbs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjueuyhu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuojzfy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnztohq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2czkpyimx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxugehpc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jergaalz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxluijr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qegyyqmn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2inupboid.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2diaddplu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xosgcqzy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fplbuspv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkijgue.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmuuoaj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuvxefs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2onfyhhsd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlilmpvz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbznvik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfmgqor.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hksdlure.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmnozsr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbjrzpf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmhktgv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxrmoht.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwmfacd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjnyrfj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaucwjx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtvqjya.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeblyqs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwoqarg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzziyey.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwistmmv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvhmumg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdagjooe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpvbnyu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkmakdy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojihhphn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtdcftq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqjomka.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2alwofsmf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvqvuzt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjotpox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2volefkxv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bilpzgkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lvruewha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxaacrz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzfcvbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2teolfkdv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrcfybm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwowqk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qczogqgb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zekhjrfh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrowyqe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyhvubo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqzkxpb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxrvsjl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzbqesg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbvvpvr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2odttyock.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wazizcll.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwawomk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2flcwpfnx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnalffm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itmelldo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqoucfw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvlcwnz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fctdlhbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuaxkpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btwgnjkw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmththzg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbzsndy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nismzpsv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozlyedl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpcgnad.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfffvfhf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwnzct.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2deypivon.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvdkpva.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdfgsyj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqktjah.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfcukuw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzsfogc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaeoevd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2phnkocho.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdsqmoc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qgppoxhr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2clnvsorl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2whacgnut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wszwnwwo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2noiubegm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nozkuami.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjtvqdq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdjsugt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkeebkt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnpmgox.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvecintg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaherzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdtxaa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqpblsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puaqhxio.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxfrqnx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2shwxkqkr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hopuztnh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoychly.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lzklgsvr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtuaoso.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgldstpz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2itduuvpy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxftrsmu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2keskzyqf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzbcrp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkfhktl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ikacrrjs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipfcgw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuffxrje.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoopnos.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hiagznrk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfvsum.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdwkzd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2begpluch.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wfffwjad.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbaaaxe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2emmrgpbo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnyhzby.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijncbnfs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fijejvng.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cygukqvm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gylcgdei.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsggrmv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mebmyywy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtverxm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tolekajd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tifwygve.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqhtxc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyietrs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsjkpm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwogaet.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjdmtg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uowkfnyp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewlaymh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqezrj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tayrokdu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryswhpny.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvfavbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncoisfj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uuupvnoq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bimgcrib.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxliylcw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjvjynj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuphvgw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkithnb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcdpsb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkfnjgr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsagyvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdhsjsw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorrzga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaxmlel.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pobbgvjs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmtcege.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxwkghh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyanxzj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrulfwz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2npgloflh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mniumyab.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkibijo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvisfwu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdsdsul.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lslaqekc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygngosvv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2srnlwctp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbojffw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutjzcc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqqcmjo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrfkxda.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rximgfhl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2faexzxvu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqdlkcd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcjxvnp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sizqvhqb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqshuygn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszclhap.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xalfzmit.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2alftsogl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hputlbug.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqexxaq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtvfswc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsredkem.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtakjlm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpvszoc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uofleyma.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bewmeyhc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwkudda.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsyoqxk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqbvfbq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oykmhbou.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2efrrnpyp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2whbatrtp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpddnnu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hxympwcm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qulkmppo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdacvyn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ullrhrak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhlobbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbuakhe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqoesuf.html


<!-- 参考信息 -->