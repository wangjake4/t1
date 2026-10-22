代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tflwzain.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxanpktf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpvkxkn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkreejp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2suvezgkg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeepviu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2crrarphv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ppriokov.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsyrelz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkstssir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2savzntlf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozloqes.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xxngagqw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2adwedvhz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhnczlb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iftxmppk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dqziibfo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2iesyukvg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlhhwdn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqrrefz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnoikom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdvrsnf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2amkzsrdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2favzpnnc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwummmi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfgflho.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxvsgsw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2edroctsf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqboajs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyfoedr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omaxxptp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mybneupj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2damoxqqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2duvkpjnm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2khyaixnt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqglkh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceachwka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzetmlyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2akwfhhcy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltgnibp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsyrelq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gssbvqpz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2giggogsv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2linxzebj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwkbcvy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uynvpnpo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvxxroh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbsjjov.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nasdjwcn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhizvon.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tjumvzmu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wquwtlel.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacavbmw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfndxyph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2orhzsehh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbqtzku.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjaxkuz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsglbqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adxwpreg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2msxztflm.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrlytrm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxqric.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daucpwpj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgawsdvi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhftjpw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hofsznri.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhbrmat.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfofbvn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdueujre.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkffirh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zllckpmm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2srhkngly.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujnzcw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvkzmvt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhisydo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yisynetg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2puzzkmzt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oabdrozy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvkidlp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qshktubc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxzmsbx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjmiyfl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xvisegxi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cujkewzh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsqvrhm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuugsoy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbyfocm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfllstg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpcfliq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyzorpb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmtlegs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nefgbdmm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknjwcj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfakicky.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtioktr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2shxwsgvu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfgutfz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzujvwao.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfvecg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wferaeza.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtemhow.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lanhnwgd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rtevmuoi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvrxgwq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrpxssc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyocamg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2evwvkwlk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpavqlz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjuiuyv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2meavdlds.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnceqwaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2otbyarwx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2drkjxtuz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkimyzta.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkrqjtn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiumckh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtehojk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqcjbip.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kljbchwl.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjsbyvl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxgkww.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mwokpsdv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2riwbssdn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqsaihb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2grjcdspe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uscopofp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nypxzfls.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2alorlmdo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgjvzrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2spltigkw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzklumg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhkyrcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsfxsik.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhorbtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqpuapr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdkgmsk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyiizyh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jidxqgtq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vljxcvgn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmxdtkb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwqgmq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yejzzduo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljkraur.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nejqvbba.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcmnlxi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxceojx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2krbzceqd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yalxasuy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qachvbfj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkedlnk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxznimm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2clcuurid.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aizehdlo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbyqvhe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nahnzwyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlqudgz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kweziufo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtujzez.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkybefcu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkdzqny.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2acciquks.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awahzasq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2diqjpyvu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rftqpkzx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pljbjztk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vogkrfet.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiswkaq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2idoqvvfz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tusescqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbdeycs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwduwds.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bctzkaak.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewhpend.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxqovpj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkdlvcr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybgqyws.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eidusmau.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjlomq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdvjhsc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibjxxi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvyvesh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2coedddbb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqawkm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vupfgjqy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2enlulssq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zroedwhf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gkogwkwo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pawczfcx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bncirqhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvmcohb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtrzgrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpgfxuq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hroewcbj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhzzwap.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmdtaqh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rydppaev.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2prtdibcg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cokoqxlp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2btrpqyzq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbpufac.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2timpgdyn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2keaqpydo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsodobf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgchunl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbgzbca.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2sawlxlnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcafszdx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2shqbsnwp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2goaueifp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2triypysa.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idaozooj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrpqsbt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcpffcd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfarbnts.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psofjgoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ledbgiuf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwvlgzu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xynwiqkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gklzbgnk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrveplr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdftase.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqgocap.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2orkqqwbw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmcocuj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2piqvieme.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxlxbsi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfnztej.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wubfjddp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mjumzunh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wthuqoro.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2deaxxwbq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2orlyjlpp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoabywv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnugpku.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjivcym.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrvjidm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cskrngvv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kplqovhv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvfhbsb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yggndzxt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbqftvo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxphqrus.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgrodsx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdrfxbe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjdfrsm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bynfywyj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcspdkk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zkocdfdu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2csfcokis.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szxnmivy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrhpxnk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkqdgeo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnujbjb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2znfkfmyn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2klmgfvgu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2prdxizhr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjzdvys.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vopgqzvq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2uyozxarv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxijan.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2djnpudjf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bmycjsda.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkeogu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuetupdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcpzukk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxindtde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsawcdn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jejzknxz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2svrztsfs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yirgbqom.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2abdtkgql.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsfcgbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxjtimd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2brwwqixj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2myihojmd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wdleavsu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmcpubm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzfftwz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzbdxsp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmihigqy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2stwognho.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmenrmv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2soloqevw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvkkgly.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjbuvqa.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2adktufwb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgkgfax.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cniszbna.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsequad.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2abzadhwy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idpovvbq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gushmcwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlqwpl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qccaoads.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqnbfyq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vguwtros.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsgiuel.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmecavfz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dglvccdw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2twqlqhft.html


<!-- 参考信息 -->