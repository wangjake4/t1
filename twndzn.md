代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2ffcqubqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2iqqsvxdn.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2ofydbjlx.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2mjkluend.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2wvrlqfgj.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2cxmnnpii.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2egyzhrwq.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2vtdabvij.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2yxiwbdfq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaunpujb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2sfjqkmdf.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vooyhiyn.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2nxymijin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2xwvscxac.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2esacxwfw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2agstbwql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2aocugmzs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2utossyuh.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiarirqu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoybjfef.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2wltedsxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2agzglbji.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2ndgxgird.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2rnvohnhk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2nlwwacus.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2xpcqcojo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2hunfwxtl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2rrzmfdxd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2iuhnqjhe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2fsnwxdmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2vgvdwcks.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2xffrffks.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2euizhskd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2afwqpzfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikzhmbjq.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2xmivacwb.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2zrorbxso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hovwvguj.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2mevwfzxu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2ppvrgdsc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gt2mpzbcimi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2zoakguou.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2ierpdoiw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2qthehbpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2euigxaul.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2djkqkroq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2zkhpbbwz.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2lsiwxsdr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2kkgmfqsd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2saipulbx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2snlvxheq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2zziyikor.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2swfmrzzv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2klkiegyx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgdrueeb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2zsnzttyv.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gt2riikvbrj.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2forgztnx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2bzirkmfl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gt2rwktiebg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2gjhuylql.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2vfhswtpw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gt2cmoyrlop.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gt2vyeahwnv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srqyatnz.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gviibbnp.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2zfxqsjlo.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2nftplaku.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2revlaupl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2fvgnlgcq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gt2vokmwujc.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gt2icohpbsd.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2nzxtktfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2ateaomwb.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gt2sschccxv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gt2pwjfkdvh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqezslsd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2rssrcigr.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2locbzbmp.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gt2ykgbhuhs.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2jianqjib.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2xvyzmpdt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2wwktfxds.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gt2edydzayj.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gt2pkcedxjk.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2awjrcdxg.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2aslntiii.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2xewnmogd.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2ifcydhij.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ljcgoiaf.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2lzzxutjc.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2ilqozskp.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2xuaxbuhu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2xitxzgju.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2kykszwpe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2srvhepaw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gt2yqzwiibw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2fwklscqq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2jhgypxpe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2hjgcnuho.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2jibbsdfa.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gt2btwwmdad.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2zmdbgqre.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sudjeyxd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2nyvptiak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2oevarelp.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gt2bhehnunw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2zvgdrbkf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gt2xhvsdsem.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2btpkndss.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2bphzphac.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gt2tdiuldie.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2rokjiunl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2neffzntw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2haenswoa.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2iylajpjd.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2iyuhvwmu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2uuxossyq.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2mnifjqyf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2grrdqphz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2wjcryqbg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2ytoeqsxa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2skchmfhk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2oqzyrric.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2tlbyswfb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2wpcygqjz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ntcfbrqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ontbndgt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2gctxnxcc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lunqrgxk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ziiiciaw.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2renkrmfr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2zvbcdcdw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjoehzxy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gt2rojmptnw.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2zwwswxot.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2mqplhjmy.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gt2npkiatvd.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2zpidaabp.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gt2iiuizdtz.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2fuzpfvhm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2ajwscrhw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynxfzmdg.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2wprevamf.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvcvacfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2cgtttqpv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gt2mievzvic.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gt2uovhhmnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gt2zdnvqzuc.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gt2hpqsqaol.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gt2xbsuyxzf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gt2flspoezx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gt2ckifxmms.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2nlfupprk.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ehwfcqgt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gt2vvwzjwtl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2qtekqpla.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2nfurvmby.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2nrtqadsk.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gt2epoeyywk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2ufqasawk.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2yysznetf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kydakcvu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2rjcxctjt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2oiwoocfy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gt2loyedzdo.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gt2kgcawzhz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2dizifwin.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2avlnqkjk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2jizvbzwo.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjnjursa.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2cgyggrhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2levuwxvl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2ggmukccj.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2vjgwgusc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2cjksslgn.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2hytmnzpe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gt2jbqssmps.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gt2larumdry.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2bgungder.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2ckpxwpje.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2gldjyjbc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gt2ywtchoey.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2yrjwabcn.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gt2mzyrtwla.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qtsejydu.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2czkoeupc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtatekky.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2qcvqgtir.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmsfxcrb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2ruzkvjcw.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2eekzrlqm.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2jsrljzmd.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2uzfcmvub.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gt2nqzxqlcj.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2cqplojvz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwxevneq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gt2xjwcuoey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2eojqxqbe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gt2sxbqsteg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnojewte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2lpzcrcnm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2jbiawfjv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2afvwqrid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2boiohoyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gt2iqzuqujg.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2exsnhycp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gt2siyyfupj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gt2zhitjptc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2yhjnnxvz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gt2pidggjef.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2cbqnylvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2hbukuzak.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2ijjzirwt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gt2mjcbfqkl.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2lcccijad.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2lbosgxpc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awphfwgm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2tfxhcfwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2bbauauho.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gt2alrgwpzt.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gt2nyuqudhl.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gt2fpgjkmfy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2anlcwnxe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2kymemtzc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2hraoyjat.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2uatktxwx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2abnhkrcf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2noyyirbp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2ndjqgjzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2jcjaocip.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gt2rfnmbxif.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gt2potsyefv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oykslggu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gt2botmpbkc.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2avwzwqdt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gt2clewoeaa.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gt2bubnwgki.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2omgqukqm.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2drqljxgs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gt2pnxvxfho.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilsdivkg.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2ktxcduhl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lobnmzhd.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gt2eiatnibj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2bpkbcbmq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvaganpy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gt2fyskipsh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2hufcjwqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrjcgmyq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cajyqqop.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gt2vbvhrguj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gt2eedybshe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gt2gldavyyw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gt2brrpsunj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2oqfgqsvr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gt2bhiqoexr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2tbpmjsyn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gt2appyxjbp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2fgucmlhl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2svsfgsny.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gt2umhzusax.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exksioex.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2pjocjroo.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2vqjeaobr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2teogmlfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2uvdiicxq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2xztqunud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2kgfuchlq.html

);
来源：http://dali.birdmap.top/Article/details/gt2yrosjecg.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2zdqlkgry.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gt2giywwvsw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2nrovdrgb.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2smkdytvw.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2jiiegtmy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gt2sqpwiagy.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfyaffdj.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2vrkeobak.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2sboahwai.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2vhohobjg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2mpsjgxzk.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gt2qpwbledm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nupprfem.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2dmaamzkz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2lztvqvbj.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gt2umlydwmt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gt2zlthrkpf.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gt2pfoabckw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2wfjrcqkb.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gt2zlrcjuym.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gt2lqgtuspj.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2qapxqjwn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axrtqzdb.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2gvigmukh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2mdgqpcwk.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2jstefyvn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gt2glthrlfr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gt2niwwtwer.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gt2urtnwhcz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2wjsnydng.html


<!-- 参考信息 -->