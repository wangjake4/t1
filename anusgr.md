代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtsxxspdlw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtovrthnmc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gthynvrplq.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtrakyezcb.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gthqkjjfib.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtqppjoqhj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtjtfpphak.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtnsvrcsut.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtrcywatvg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfnjbotuu.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtronqfihw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdvhggkdm.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtdbfilvhz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtastnjqwk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtacgckwax.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtauvfnrbu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtnjkbjgye.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtixfoihwp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gttnuufeqn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtnxsyvguj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gthoalftsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtzbjcptwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtypvffela.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gticntwocv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccgbmquu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtayzcfvem.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtyfqfosrb.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtrbqivztb.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtdfqlxzyf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtuzhdohcw.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtuqkdixjg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtanhvoakl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtkzqhltft.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtffkbazcd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtxqsqpwft.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtomrkfazf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtccuyxmga.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtbjhacskl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtpblsziax.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtzzzklnpz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtcrfagpck.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtychxacwb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtlgifqwhm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtaoavyray.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtsfshdrvi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtzsymlpon.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtvewsglzu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiixrasvk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtawshbjes.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gthiokwpnt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtonigfadg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtmkldgmuw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtbzyouvwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtghtepksb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtlukkrqcm.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtdgukzdao.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtvcxkmpdr.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtxkohsdkz.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtkxdwapqw.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfgpbmjg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtinszbulb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gthhyyijhk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtthtabqhl.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gteqashfpk.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtosgiwtsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtpshhayje.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtjgqnjzrd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gtmqmzizvy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtirahnnek.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gttfexjsik.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gthwbibysy.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gtmyaugbkb.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtxxeogkxk.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtpdqvylbn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtpwbibcqf.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtjioulpts.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtimmedjsa.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpkaelbf.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtkshppixh.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtlunclvhx.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtahdobvaq.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtvmxicfyy.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghtfwvxb.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtnhontjjt.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtrqxrciqc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtusriyfyu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtuyzvaifl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtyqhoakhy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdmlaulu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtanzcjyly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtevgncbou.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtispwrytj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsrjfikx.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtycgdasvn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtpzpyqxoz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtnbatxxws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtmijkhxly.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtfdaamlzw.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtwkkvkpng.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtefcksomo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtbyloppod.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gthzqrudop.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtbksqutfx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtuyjattgd.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtrclzemar.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtwkvvhhrk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtuycvncsq.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtqmokmzwz.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtxwjzauuj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtbbrwnxjs.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtwefpuphi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtwivqwgjg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtszflkigm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gtxfyfzjsu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtmizkbzsa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtyzwydidi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtrihqohzx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtebtrxyvi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gttvyozpul.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtdmkbwdtj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnxpkduuc.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtmuwiferz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkvtznzsn.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gthqvocvdx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtggoeejoo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtelkqaxrn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtotpkdjsx.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtkrsodnxw.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtyfaslnbr.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtqzvnnybt.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtlazeltqn.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gthpebqnrf.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtyrtmkvis.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtknrwppgi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtlgpzwsnt.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtfijlwrhz.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtdcmrrwaa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtudszocnz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gtxoxswvai.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwrzlgeb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtwekeugwe.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtckgapdan.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtrpzamhgw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gtduwbbdwk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtqihdjzll.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtqeabedrh.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtcmcrrljb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gttyxryhbw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gthtrutxno.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtfutkongt.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gttjwgintr.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtpugyoxes.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtgbretwhn.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtoqnktbjk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtjrvmqejb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtypmldmsu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtusdntkzx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtgvmwsbtb.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtyuvtunrd.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtixqnixjy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtzltxjrzi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gthqkbnsli.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtonzjmgup.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtkfrmczap.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdafelkw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtixqynbga.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtxhwqgkzb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtfktprywg.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtuwecwawn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtguzafmgy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtkzyleckg.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtqwwdzrvf.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtqakcmqmx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtyataexfp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtdcgfbopx.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtyolrwvlp.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtetewyxek.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcngayrad.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtgeryzlmg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqxlraisn.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqmmrwvf.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtcgtubkwa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtrszohaua.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtlwbrwcon.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtrjcarcpx.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtzymgxady.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtcgexielk.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtsiknbcij.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gthiphlivk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtjfmjnatv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gteouxxqqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtxtmospnb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gthsuqmotv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtikmwvmfg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtnkamfeih.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtmgxltkqj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gthqxitvco.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gthteteijh.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtjopasryf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtbzdouzlf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtproycaso.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtepdfojxy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtzjujkuiz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtitnqwqlo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtlpjlrwuw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gtoeswdyaf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtxzbpcrky.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtulqvaysn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdilqswt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtrhamlwxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtrbkwldtv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtmvwkroxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtpgeratco.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtrwvqbpwa.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtrlbjgxtw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtmmaeoqek.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtsqdiayaf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtvgjdftnf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtcnnnyyar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtuqxokjyq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtmfolohti.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtefsoqtwh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtkztdmdzp.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtymjtnpgx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtzwzzlcnz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtvfodewlo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtmhyeneyr.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gteuaasjpt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtlajujzja.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvrdtmaf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtwpunycso.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtyfrwuhdj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtskarjnog.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxykndag.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gttuveurgi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtnzmrckrp.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtvcfqyufv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtnsscdnnu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtqzwcyzsf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtwuwjgvxq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtjfveqopp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtlgqhuxyi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gtoswviexq.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gtjodllscr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtvmadknwe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtqxwtagfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtcjtwtile.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtpdibbrgg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtzukjvohx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtylthhjpw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtpgxbdkol.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gttndrsrrb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqnypagow.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtxubjnchi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdtwnulaj.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtykebvmwb.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gttteawyug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtoibbraiq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtekfvwguj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtphgxpesi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtyojlehmy.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtmbxxosxw.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtsprjhvga.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtpnkxtoxf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtgwqiuccj.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtjxhyxpjx.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtekkqkokx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtyiiwsdtz.html

);
来源：http://dali.zycfv.cn/Article/details/gtmpwfkvpn.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtsibrsewu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtcjvnvvzj.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtnvjbgrpi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gttavqgnql.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtnhdimhwy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gthhvvffua.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gttvdvwnfj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtpovosmdp.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gttzlxjkjw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtynqlqqap.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtlkykskeo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtmilbqyxb.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtwbvqdrxp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtdvdgeerx.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtedrzjrxd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtgdllifjt.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtdhjgxdwo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gttszwkkcp.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtitjgbvae.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtymtrexna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtcjugpqgh.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtkprkbnsr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtebdctiyf.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtusueqiiz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemaertgc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtzbmqvweu.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtutqdjpns.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtyxrdulwu.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtotqonfkt.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxhcsmegv.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtzemzcjom.html


<!-- 参考信息 -->