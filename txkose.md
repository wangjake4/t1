代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtkhpfqyow.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtxxwhsvcf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtnmerjetq.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gteufdvuwk.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gttkuturrv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtyfsxmdig.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtqgmwjlbx.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtefnhbpfz.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtfmhaqtzk.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtcqtpdftt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gttwlrymue.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtmfzrvfsp.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtkmwrcajb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtcyxmsivf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtephfcojy.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gttbrucccc.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtqdxjhgro.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtppaznfts.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtaipcrewr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtdsstlcqs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gteqxvmgdx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyfrhegis.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtfqseodfu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgarbajvh.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtadwykirx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtugexkyrr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtgngwplqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtxclpkxnn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjchjvhu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtqiifbomp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtrnmakyal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtadkexiqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfnwdbigx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtzmehparo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtmqmzothv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtnwwvustw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtabsddiag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtabnaxzrn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtoqvmkuvx.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcqosnimp.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtgdaopyya.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqojlgdyl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtcmmuyelu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gthtbyjldg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gthkjbamek.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtjajbnfsm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtqowmvicz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtqbtbkixw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtbkoerels.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gttkdxqlyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtwzsnqssr.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gtydkppdax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtzkukixor.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtqypcbhxq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtrcnbhani.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbkjgivcj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtnlowdpxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtvgjesmar.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfvgvdfop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtpfjsxags.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaztjurk.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtfqageect.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gttyjpsduc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtlmxjiust.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtcxwrvnmf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtylleqraw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtdzehviqh.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtziqqzdlz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtybslqgno.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gtxxxezyed.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtqhvuiwdi.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytmehbkl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtcqulgbmz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtnrifmldt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtancvessh.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtvemxsbgf.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtughqgqbd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtnqmxapfv.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtcbcypbwx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtsyjilqrj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtvcmeagrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtkhxxmxhb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlklqkue.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtijejkwnh.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtbjsersfb.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtwkzoqlzc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtmtedjnvk.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtdqejsuak.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtfhoztmpm.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gttkgeqlwn.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtkscstopo.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnhvmujf.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtbcauympm.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtgutdoyan.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gttmraxizw.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtjwcovlxe.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtammxtypm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtxswipigg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtzjvgzsff.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtfovcegel.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtxricyvhc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtbstuztlt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtmkcrwxjt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtohhrzcrk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gttmwophpg.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtosncsugs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtqrerppjv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtsmambrve.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtlozmjxcz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtksmzjhjv.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtrgpfrvnz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gttjbdonpp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtjiiwjmmx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtdkssembh.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtdtrtpnnk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtsjbqityo.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtmcovunra.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtqrydeshd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtryuustln.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtrgvvxpwx.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtandzlfyq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtlbzzujoc.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gttnvfiuik.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtyybzqqto.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtpocqzgmm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtcfxuqpyh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtvzinuuov.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gthoifvjhk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtmnlbcamn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtxamcwkco.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtqrsksmdf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtulkibfhi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyfhxevro.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtpgjcpcot.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtstjioraw.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtpasbezgd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gthzxdtdnv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtygniypre.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtsprlxjvd.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtxqiwuaaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtscefryhi.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtfuwnranl.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtvhyvfpgd.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gthionwmnu.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gturbmdeax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gthvontpwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtbjvslzvo.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gttnmzncfi.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtsxjizvza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtetxbpurh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtdojuudnj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtdmoajvdg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtzcksouvm.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtjebdfmkl.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtxwcarttk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtvwjhgeyt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtrrknyfkq.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtwgukzftz.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtyioqxbeu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtulmhxcwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtibgsgycu.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtwfayejuv.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtvzbsfzfn.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtxluyhbxi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtrtxhlont.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtriuflbmx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtiqtmmzwh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtvssodnet.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtpownnvjc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtsljmuxou.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gthfshgemu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtdbskvcnr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtselrwqtq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtccjezxyc.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtfndeptsb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdqmmzda.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtxejgptiu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtqlcglknb.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiuegivo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtndjntmkf.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtunvkwqij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtrvtmoubh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtguvhmwqv.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtgbdcuxgx.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtsjaelqpk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtuifedeqa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtoerfstvm.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gttghemmgc.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtudggivlo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtevetdhkx.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gtxayauntl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcckojini.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtqeqgsadc.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtllnuqxzg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtesdiamsb.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtamtrfbug.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtfnsphioa.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtuferjqgz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtajzkyeuo.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtpvdjlbwg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojioexhd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtzojrwthn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtlxinmtzb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtszsygpcw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtmiwyguhr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtwkfczduh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtkprsxeya.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gthuhbbyqe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtclpeiapl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtepyomgce.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtpaqrwnfv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtwupiyijz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtefgiqlkr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gttihumvhp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtokkzbfmg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtceepenea.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtaqlmpmnf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gttcczgvel.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtejebmguv.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtrnrqxrfc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtxrqiypqi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtvykqmyhi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtoyawnget.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtuwzendls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtsncvsnwk.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtzndkeofl.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gthaoynphj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtzgskhble.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gteacrexfd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gthklbtqem.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtfonqhkgz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtewtxyxrr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtnyiqttvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnbhthrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtmuafqldf.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtxnotggem.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtpxzdfhfl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtantlufio.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtqmmqvpbp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtotfaeyrj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtjwkwjknj.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtswkmgdoq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gthqdceqjk.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtapawwnyc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gttbifcnyt.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtecwgjghd.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtlwrflodl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtcaeqhqgf.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtquhvddyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtxvqombkj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gttwubhnoq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrzhmvkpw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtyzzitunb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaantdyrh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtoxratlqp.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gtvxyndyhd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtrfzapcbr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyizztmd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtdtghbqes.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtamcwcqkr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtvxgspozu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovjaxwrh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtzvxrhffa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtfpozidcp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxdhqmabh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrrnnfir.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyqqmggme.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtmfscywfw.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtifhrsnar.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtdnqbnbcj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtpczezfiu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtndsoatqa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtyeltvkju.html

);
来源：http://dali.316326.xyz/Article/details/gtmbksider.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtmbixobpn.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtkhszmqos.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtohcejwtx.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtfvyycaxd.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtzihxmpeb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhongyouzk.top/Article/details/gtlhtaolyl.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtltxotkrc.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtbojjkqqe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtmgdzanad.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtoxhrzvlg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtkjtxusww.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtwgsenxfv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtzpzbzcrb.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtpuoinjfe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtudlkezue.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtidmvhcyo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtleqxagoq.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtoiibucrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtudkawren.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtskzgzugc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtcyipsmuc.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtrdhoitgm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtntbjishn.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtkcxzlzqf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtwboyogpe.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtwpeyztjm.html


<!-- 参考信息 -->