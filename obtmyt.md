代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtolealave.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtlcxuitks.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtzjfezdck.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtqkaowpkr.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtyiwwewhp.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtrtibfaaq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtcvrdlrva.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtldwdpmad.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtaehkpfyl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtvwafvcsd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtzqtwdmlq.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtynsvppsz.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtpxieudnl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtkdilikzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtrtwqjazq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtgudijuxa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtwhycujso.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtersltknv.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtmiishyhn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlxwhsvik.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtxldxujmb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtizoptdlm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtlfcvoimu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtshxrumct.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtutddiwpq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtacqvhgkk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtjuutcvpd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtmuqyepzq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtezifptjp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtxgzeplnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtmmxpwcrn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gttodiiivo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtrsvajeww.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtwppnxnsu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtwerevdcy.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtjinbjcwf.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtomuhwdsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtfxdkucsa.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtrwcbwavs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtyhptyfsd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtzafrnata.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gthdbiqvke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtkvzzhigv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gthnjmzlav.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtrkbmvgki.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtngzsfcvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtzwgdvwel.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtqtiizbdd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gteqvyyrhc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtcsefmikh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtclpepwsr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtghfzhfbb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtzjpxywqv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtoipycxjm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtfdkgbeeu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtxvgzaaij.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtzxsbkefa.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtpqtvvrjw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtekbhhlld.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtzspbbawy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpgojcnri.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtliogrgnp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxxgifjs.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtwjurebqp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtnxpnjwom.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtaquxegsb.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtbkshqwas.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtomhdyczw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtzkurcwec.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtwehhorij.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtyhkqaxzu.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtuwhzqhmm.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtwazsxnii.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtoiuxcxsd.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtddaabdwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtivgpjeqk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtyneqqgxq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtvyhcqigw.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gttqodxksx.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtkcwboznm.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtcazconon.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtokifeyvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtlxvdtzko.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtwqypsuxi.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gthqogsypx.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gthdramwyw.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthbuonlfv.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtwrlqtwjo.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqlwxxpw.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gttnhsxyic.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtbyovrwoi.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtqztihxfd.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gthubounqf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtdlntefds.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtozeszmgf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtlfkldlxc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtsdggfium.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtvbanjyoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtydrswvpe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtqjijubge.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtunsnevnq.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gtpjlvmsiq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtlapuagkl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtovmodbqa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtqinmuhta.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtxxfajoxk.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtlhxrydhe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtzslunhwj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtpshqkzdn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtlhncwzjn.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtbznuxxfu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtwypvwwyo.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gtlneeevxx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtddtabjch.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtdqivaiox.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtmxbwgrzq.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwcyhzgwg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gthwqzfwzg.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gttsqwgzho.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gterlysdxj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtyihdyqpa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtexmroiyl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtzhecwhlc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtvoujrmnu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtefsytxvm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtifjiiiyx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtosqvtdxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtkbrgmhrn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfxgijeij.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtgefiuyqc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbdouezx.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtykqqrduj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtwtldmlxn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gtginavgut.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtdzmpaexu.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffculkfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtssrafeea.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtwwgqcatc.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlmfsfyy.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtfshnrilc.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtslidijst.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtrhxfdcvm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gtgpeuyytg.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtetaarjbd.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtrakxohhq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtjkqeharw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtjqumcubk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtokgwosbp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtglznovvw.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtnyudzldw.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gthazqpebo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtmpcaocnc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbiotsmh.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtuzjuzlcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmerfcoc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtbxusclgn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtjeeydsmd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthnsoysgu.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtgyeykdwg.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtefcukhuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtavludsww.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtkbgnuapv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtcapzrugz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobbelrpe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtizdaiuri.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtvaiwgzwt.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtibxhyqob.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtwmwwwsgb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtjnpwsrie.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gthvggpjer.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtjlzjgepw.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gthkxnogux.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtgllqammb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gthgpjbphn.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtjgxjurqd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfitlmfnf.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtshadeuyx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtghyqkqfl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtpdggzhqc.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtqdczhcsr.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gttmvfifyi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtabnqbois.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gttwmgktfy.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtmyqjapwc.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtpvmjzmlf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtasulftrm.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtaijudntr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxgwahjsr.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtetzrsgtb.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtgnmsxrvo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtcofqtijk.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtzwlyiaxp.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gthczximyh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtqtviufgn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtzoexdwmg.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtkqvngwvk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtoruodtrv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaohvaldf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtrxmjfrfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtoxuwktjo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtubpgbsxv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtzpcxmbaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gttlpjmwrv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtpucyonzg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcnrwiibx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtxbljnlcl.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtytuxfpab.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgedaqhbd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtpsiceuhe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtypqfefag.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtvfkmefdv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gthgykjvoo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gthocaqxby.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtnhsyzppa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtpojzicpt.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtsofaripw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtdnkufykm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtiglkgzus.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtqkbfvzlv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtdoogsqkf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtjhrxcaat.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gteehmfvbp.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtovmnqgqo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtglpoxzeq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtauafmzfy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtapbdalcr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gteerndcyn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtwswkpmoe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtnjttbtaa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtrvmxxyhp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtvdfqdgit.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtixxioycs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtxymnayqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtjlyechpr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtmeisokid.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gttzpswkdv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtglrjhfdh.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtimxkceko.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtudhvjiou.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gtvvozkqxj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtrmilzzgt.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtiszbqjyd.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtrnuppwyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtbtsbtbsw.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtwvvjchif.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gticqycsop.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gttysdrdoq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtpukphyna.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtswdmywft.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtedryoqfr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtqbbtphlq.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtjcbovjpo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtitbghzki.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtfoajunxt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtvnkvnlhj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtgewwwosr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gttmmnrtcp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtqnnexnou.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtjpzjmhve.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtrycdnhwg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgxvtgqtc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtbdwhjgkg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmyuckear.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtcluadxau.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtosmgpzrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtxxeihtxh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzssdpkv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gttffcjexh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtmypjbpaf.html

);
来源：http://dali.jqgfzy.top/Article/details/gtelgotwfo.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtoehvkbwo.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gttrjnppjo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtcbquuekt.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtnyjwhsbe.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtvuhirkyf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gttipbpomq.html

);
来源：http://dali.ppjwa.cn/Article/details/gtftxapfho.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtvlieusqi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gtbidkxijp.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtmkdegibj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtnqpwbjma.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtobqpowyp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtazjdhjrh.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gthvbqeqkn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtqxdjqrok.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtjwympohy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtoaymxear.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtypxbznai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsrlxtat.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtkxljpyhs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtcpphvfjs.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtkhvhlwto.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gtlwveznsi.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtjzwunyhi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtutynsmkl.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtidsfnoqd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtykqnvnrg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtmotmupoe.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gthjhwiney.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtcebxvely.html


<!-- 参考信息 -->