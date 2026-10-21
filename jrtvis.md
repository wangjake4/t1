代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtoxxtfywh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gterzowfuy.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtqfzwkvau.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtijsvhpwh.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtehvbkpsh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoezebnlv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfgkydbu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtjkumaico.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtaqhfjrpw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtytrnawct.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtdgxfdezs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtiudcfvmg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtrugtglpo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtkhochfjw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtdoaxvkvr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtlyokujho.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtvhkhkvoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtarjckskg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtbbhihbak.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvdlotje.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtwmkjovmj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtaklwiuqp.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtqxraihge.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtwkdtgsdy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtwzfvlfte.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtnfeydehb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtqngoeyfq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtkpfhwjrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gteiikwimv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtgbezlauc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtznxjibod.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtctxgnhse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtyfcuhfxx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtjrnemrxn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtnnpciomf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtmjryxzns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtafmcbfoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtugrrbiec.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtzsndqaoj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtgifgigma.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtzkpyqmup.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtofzvpvfx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtncjhtmjn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtpytjnnzu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtegwquiem.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtbltfodev.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtmjozbeng.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtvdkcpfca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtumhypjjb.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtqdphpiga.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gthbjmpxez.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxwvnjsg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtcsyrkdqp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtszxozjzo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtjgagjcjk.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtjmsafgcy.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtrrlntnyl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtlkyqfyyo.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiszaemd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtznvucydr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqvgbkpl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtvmxnnlyp.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gthtzuwfwh.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gtgiqszhih.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtmruciduj.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtzkpywzwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtfizztmmh.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtjbuasohl.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtrxhoptsf.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtcfhycnds.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtxmyanqxb.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtapjwovym.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtyxczhucy.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtzwtmtnvu.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtbkuhwwhs.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtsmbgzyhx.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvuweahh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gthsrvigwz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gthkuncueh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtxpprmgdd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtetnwbtbg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtjpmzfgjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtvjpogrqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbugaafb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtliwfuzve.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gttdwbfvjy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtmyceeafj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtlarcakky.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gttmfdlntr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtaivytzun.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjccjlygg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gthilvepzp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtocimaupf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtacfmtxyf.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkregszcj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtphxjltdj.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtcqpukfoy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtsoulamxp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtzqaeibka.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtssfoxtsu.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtnauwxqts.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtrixcjjkp.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtcmlcydfj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtqrkhstpt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtliyaoizg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtxwkzmaai.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtskldyzrm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgfypawe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsvtmfdw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtgtkmusht.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtjfcjknvw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtdklpotjl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuqendsbd.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtuzjpezaz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscfjamjn.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtwoypjufk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunzumhmx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtheovehnb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtsixnyamf.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtndjtktvb.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtvqvulwmk.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gtjjpzlwdd.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtvazbddrx.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gttqqgilkf.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtghpwlqiy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtnquzgcru.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtxebegrnx.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtogtsjvog.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtzfqifddx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtktmmmise.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtnrzxnaii.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtmxpbpidx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtrgefghtk.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtijoqnvqg.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtdsdzcahb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtjqutshrl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgufgkenh.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtzjokrtng.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtfxbluizh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtebrfzfnk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtayhuyzdg.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtnljavzyn.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtylqstbpw.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gthpudikfa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtrjxuwnlo.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfjnneuce.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtemynnnro.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gtsxmckwts.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtdsemsvnv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtpzbfycoh.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtzytfiyfe.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gthdupsutf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrekxltkv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gtewvnfdwk.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gteoerqkae.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtzvvwmkvj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtievvfrts.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjofdbjap.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtefcydejr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gtnemyqbii.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtoktexxba.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtwmtyrjcd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtmniokyay.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqjdaxeh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtstdyvzsv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelmuyfsm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtykiqhbqa.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtuaahrjao.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtlvdorvmr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjzsfiafx.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtrfclsnoh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjpvpioxw.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtcezsidln.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtntechfgu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtvnrxeggz.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtlsjkylkt.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtlzcwodpx.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtnjtjqzfc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtdhbrjzlg.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtokkrvkku.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoguffxfq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtfhwgfmgc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtgifebtbn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqiackok.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gticmlfegp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtxmntawmd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gtzvcgwzfd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gteacijxir.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiktrgtg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtihlsfqhx.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtdkqzikul.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtaqnxrrsx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gthurtysuh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtlbwscwmn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtsquycblp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtsoudqwzi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gttxneucek.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjwvxhob.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtpneuhmpa.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gteftomljb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtcpzieqaz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtmktejidz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gttsmbqckm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdqwbmhh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtcnicrkzb.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtvapsvqhh.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtpkpzdbrx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtortvucjg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtnjznqppv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtwmyewoxp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtmmzcysol.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtuniflzqr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtffmazpad.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtgaimenil.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtajjoymcv.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtsbpapkvw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtqhqiwpvn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtdcvslnbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtpswahgri.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgssgabav.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gtwcurgkaq.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpahwjpqh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtzdincveu.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtvrigdzhg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtnebnbobr.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtwrbjkoyu.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gthuhudebh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtmozssaay.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtywhowhxu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtgpzjbkvh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtxgmxiknh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtceaebgnq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtcpuprlmu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtbkwyzsss.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtakffttuq.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtlyzcjhfy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtpslkqzun.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtpynyegdh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtjuuqlips.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtrtpfgljf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtbvkqstlt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvgtpmcd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtpolhgvoq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gttwjpckxf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzwnbpoxp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtcgtootvt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlkkatzgu.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtynawogvw.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtihdzdzgr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtgrweqvmj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtuapcbvuf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtqqlgmtno.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtanrezeql.html

);
来源：http://dali.gogol.net.cn/Article/details/gtrxvbxxsk.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtefrvnxjs.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsdqynar.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gttuzzuzfh.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtfdumwpck.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtajgqxiah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtvowlsfug.html

);
来源：http://dali.meibo888.top/Article/details/gtsoackawr.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtaecmktit.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtbietazhp.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtudlhvxgw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtrkqslcek.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtijoucter.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuzshcba.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtwrsdhnck.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtotwnqzip.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtdcvrolnw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtesbvkjsp.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtecuhpknv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtxaxksaoh.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtcvfftbaz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtuzzrzaxx.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtqdewlfkr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtocngmlvy.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtbgrucvps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtohrsdwgt.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtyzwlkiyq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtxbksfkvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtvjmaanyf.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtcwlfsorw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtnjvmqoib.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gtuxwwzxlh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtzvsdxuds.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtkjmjfrwd.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtmmbseqdi.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtqnksgmxk.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtpiixfdtc.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtondevbph.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtxitwtqnq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwioxcdyo.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gtfhakzcwc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gthrjbxyor.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtjkikdxfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtptkohssu.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gthkgzinpo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtymbwwbic.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtcotgvsxg.html


<!-- 参考信息 -->