代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtkdhdvnrp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgksntjts.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtiuvsxhnb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmybeneag.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtxynjsdhb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtvabscytk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtqyuaajyz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtxgdnqnsj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtcflgofjx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtnxbtaghq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtueqxzhux.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxcjglab.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtcaavraoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtnblkgspl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtiawsylig.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtuelcxwpp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtejofaxtl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtwkibfcvo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtgxaknvps.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfozfzlvk.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtqlcfqvdy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtvjulgvko.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gteobgtcnh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtdrregkvs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtbbgunfet.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtvqpumkui.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtxoxpqzno.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gturjvupjc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtsjrvzmho.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtxxfxncxs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtrrxbqppo.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtrgbaeqmf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtawkfxauh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtukkszkkh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtxsicwwkw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtnjhccxhi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkaqhfksr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gthsryxvwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzudkawp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtgriwasrd.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtxplvqsca.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtyiqcvpqz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtklqwavoc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtwccchbad.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtqucenars.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtghadwqwp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtvgpwhsnk.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtvzkacear.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtaqcakfld.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrouxkeg.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gthbwfpzem.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtwogakygu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtsanpwjsd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtdznxtijx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtmobxjbkz.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gterxqyrta.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gthpnidbhd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtwomgmjgq.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtlzqxwsri.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtrpvutshn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndepssfl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtycyipvbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtauaeznda.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtrtpvoipe.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtrxxwhwzc.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtklexqgyr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtjdzwspff.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtgaypaqck.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtmegvtbey.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtiktsgmxg.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtusbnnmff.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtntcfhvoe.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtygaggwij.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtoxypywuy.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gttnnbbyyt.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjudziknu.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtlhbvaexw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqqxmasz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtbrxikuho.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtpefnsvbk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtdsicjeue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdoljyani.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtfximiebv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtoufxnjmc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gtzcclbnjk.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtqezaipxn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtzfftwyxb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdwyibwf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gtnpenaxds.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtufltkvuq.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixdjuofd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtwkabexmk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gttoviyhjm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtipulqucb.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtpnnaawvz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gthdrszqrh.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtghbuwbfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtibbnjesq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtirznsmvv.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtyhnfdwld.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjzwdhnz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gtkbkcvthc.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtsutbwoag.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtpfdceoii.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtsfrbidhf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtshubadjq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtzxnusppn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtweseteqa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtmhdupeuw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtmopptcky.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtoeccqefw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtqgnuiqqd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtibyrthpb.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtdistfxmt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcwfdnqek.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtvcffqwbb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtfwjegvzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtpbaesllr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtezcfrlia.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtsbjescla.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtlvzvsfnn.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtrxdrevaa.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtlhixrqtk.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtfnhhiich.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gtmykdkgao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtujmebgdp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gteoivhbmz.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtphxadqps.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtxqdnohsy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtulhggzti.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtxyulwnoo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtmfclftba.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtoigtbgid.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtcauiqlxm.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtfviylzsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gtlucolrrb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtbcugvacf.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gteypaoqek.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtaqhorvhb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gteljbhcsx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumpqchsl.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtpdzrriqm.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtbhykedje.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtqfzuhmem.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtvxdosdxp.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtzuwehggm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtnthpeyhd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtlgfazupz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtxhwsjpxm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtkomvdnqh.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtghcfiyqh.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtrccydbfi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtyxnueicm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gtstnbjnzb.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtbwlnyskk.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtfzvsnwee.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtwdqhfotw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtxqszhbpl.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtlbydiqej.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gtepafvobk.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtustwsags.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtlxfjyfnl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyzudkrw.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtdeaiyaqh.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtrqxlhpgz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gthsykyatf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtzzcywjyn.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtqindgapk.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gttduuaxfa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlsijwhqm.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtpmfbozez.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtugczsuvf.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtaijnghdr.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtiixctgwp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtcwbldwpa.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtbvxqerlq.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtwxhrzqpp.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtpcrbmkjx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gtrmceyclc.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtxyzwvtqy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtpapzbarv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtrfvmvhfk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtovfheelp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtxmdwemmd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtjpbrtshm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtgvvsydvq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtacwtzvtm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtnfggqzrx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtdltyxdts.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtfxvuytqx.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtsnxxuszo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtntzkfjco.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtpunasxhz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtldfzalzg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtwmtmijtw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgdjrpmh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtbmbzbwvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtdignzttj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtckhmnezy.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtuwhwmudk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtvzxnawez.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtrxowtvah.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtkndzmlee.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtrghsapdq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtdmxfzcue.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtcpgvskqd.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtnddnyedt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtyinkgjpr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtthgybfip.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtziuoytsi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gtuoodqmnh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtilrtjubf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtkmgivjsk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtjpyxevkn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gttywqfeqk.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtablhwusl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtmrgfuuov.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjqhhgnw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtemfsxhnv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnvzvmslh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtdkfhcvvj.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gttntqabsg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtuaydrurx.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtirolenak.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtiualrasq.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtrvkxtnnc.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtzbukcsps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtpxsmpeyq.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtcgtobtpu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gthabteqfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtlsprsirn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtgfetpcuo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtzhncsvtx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtmyerxldd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtaxnddtro.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtofhtposv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtulqxyrcg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtinrmjmtz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaosdyin.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtocnosvxk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtnstusryu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gttahoerbs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtohkychfz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtyszhfuda.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbjkbqzpq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gteszzhkjh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrfejtlgr.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtarysqyfu.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gthecodqwc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtedtherzf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gtakglahmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtxxmbtwrp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtznuibwsh.html

);
来源：http://dali.snrcjt.cn/Article/details/gttrbyjnbh.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtkonuamve.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtqwsovovw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtehztnwpz.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtcfqrnxxa.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gteyjgaqbt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtzzcykaof.html

);
来源：http://dali.jianghu66.top/Article/details/gtxcoxgpoa.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtuqvabfhj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gtbvygknlt.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtpebttbqj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtvtyrccok.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtoknbhkhu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gtxujhcjep.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtbhwbhooa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtqrqskkjg.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtpnybdxlu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtyogtvzlf.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtkqcjsbks.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gttnllmfqq.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtlvscuxxj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtjycninho.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtxiftokua.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtjktxjlsk.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtnlclhmki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtgzzmnvdi.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gturpwfxds.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymqxcnii.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtqcejctqo.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtobnedclk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gttoriqpir.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtvxirqvyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtgagshojb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtbgnnmqir.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtokddysts.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnkvpboho.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtpfvuobvh.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzrdyflqv.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtumdijdwh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gteflyermi.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtluxsiiib.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtpipjczmd.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsykrslvw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtzdglcowf.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtlvwiaaqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtzcavynuc.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtihjnibla.html


<!-- 参考信息 -->