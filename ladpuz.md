代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbjwaul.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uatrybhq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceygrnni.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pchokxwt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2czqehrom.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqenqab.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gomwtjlp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2elcrztku.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2oktplcpa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvkqlbk.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsvdurt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2momlevjv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrlqvem.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewolgwns.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2optkgzqd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvidksgi.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpxwxmc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwebfrrk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkqvece.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pneeynhb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gwotpgxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyabbr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sndxkqxd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrnkazs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ybozahhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dszdgwut.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlodiue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbndeh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2biazvjhb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxktixh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdbavlf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxizetlf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwvvnmn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbxazou.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwnobtr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevgnyaq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbamflaw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxblrwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oodfmegf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2quymzper.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnlgqrx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msutlwmi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpqflys.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jalotysy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkkumt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2awwefics.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvekfwbq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uiifitdu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2daegisqs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lagqgmdt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjqbhqn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2piyhcjgx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2exfadwov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfadzghe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lcchpxps.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkvohlc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpuzaxu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohiorgc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmzdfmk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlvuatk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2syrolnmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighnckzd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvprxhr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2akyacjto.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2whkovuep.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvdzzeo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhvlqlt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcyzch.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummagogr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2puiosdco.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yypohvhm.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhwapk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyuopql.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2byvnfwat.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eagechhl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyhsfqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxerente.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2emgdzxaa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2punidrmf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxtqrwu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dfacrghj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2olezhnki.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayptdghb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjtyzql.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jinbtrlc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eactclau.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2psvuohsc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cctvmydf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uoikbgzh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2veveezeo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxqpsor.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sudkpjni.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2esnftxmt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfrftqs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvefgd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxckilyf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxeezzp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iohrnaey.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gllgwabe.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkmspyt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqdkqdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxjgjdl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2izowxhqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfkqrzw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwetkhu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2neiathpz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nugidqub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwftdisp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2soaaeksj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwkkdvr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2guhkrxot.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoifoxq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptvxien.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkikjklu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmkonsf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2iljohoqg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmyrazq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfiqql.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzvhopj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wfigunlj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oovkdkfr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ceboifcu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yvifdtdp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2flbimjug.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzwdgcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnawrbi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mctemkhb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruanzsrb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2evumlwsi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdwrtld.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzivnivp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtpjqch.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ngozdcax.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2czqgcuhy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2smoymyqx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgriked.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xaavnoah.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxgbsnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taqrccjt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qtniatzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2culicecm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vksmoaci.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjnekoj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2itkhdlbh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ockkmwzv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfivtfmz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhtrlfp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsqlmha.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bllubgpt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sarvhzuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuqbucy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cdntbblv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjzcrmm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnrkcty.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmixacs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvmdatq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zotbalxy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bshkxnvp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akaodnhe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vmowobqm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pqecpqil.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fydjeoax.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjlwnur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2grxgoiyj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeczfia.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvoarrr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoqzocr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsadced.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2adhkboxr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnhevkt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltodcdkw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatuqdk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbixjzx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaaanby.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anqyxetl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2imzzjeja.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdriwgad.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnoqlbz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcolrnx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2arioszwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwhowvq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixklzkpj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoqsjgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnufvthy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqpqjju.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yskvtowf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhapcay.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrtsvls.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2libdureb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gaezcgpl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2damrbqgm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gblvqznt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdkyhwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kphqusjl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpkozup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbuonii.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqevcml.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmmhmmb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iodrqrlk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkvgpdg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvcgzgm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkajgdky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hjemmjxo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xnowbmbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2snwbnhtw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fawehmkr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwkqkcw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnndfhdd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmwstih.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2apfkngkc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcowcil.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qehdyytp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjlmyuo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkxtxhr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvpvpqq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmxkhmv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxgtlps.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbukvrfl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsjiklf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrgbpeg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvduneo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxanmgr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxpyxff.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uktcvspi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2frovqkqg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2saqvrtcn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2finzjemb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbvycnm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjgsdyw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxqskel.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqdpynl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jewhyjzx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xudrfhrp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cpffgzfo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyijeno.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrwuogz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcreyxd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpxqcc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvjzcpf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kptnglri.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfixgvz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiefejvj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bddcdjdc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soskxups.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2agbdulgh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tejnsull.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtwguep.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgkfvoz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwvmlyz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwhnfix.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsqkor.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2staquvyl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2focftxrz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phekfbtk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iukmcfos.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgyioao.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwljuyz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxspcps.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxoycg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pktfhovu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjewxqy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcqmory.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qpftixlx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkvjtir.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhpngkp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ziobydkw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2braftmkw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2anvsesgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icnlodum.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jufjbusy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgzcdnq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxwzexo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjeimd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnskmuo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2swnixaun.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxorunf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhhadnd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2owxlfdpu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2prtxddnu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sidccayc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hsynalgs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvjijdu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2voegglcu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhhesbw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zehkyzov.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2aibuodnh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gineflrz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqazbysi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvkhbhg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrjdlkr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuziqnp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkhpckq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nssfxbjy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxtuha.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnecvhgr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2grxazvwt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwykwhy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqspxwk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zohogyte.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbexivq.html


<!-- 参考信息 -->