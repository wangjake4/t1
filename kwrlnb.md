代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2nubjhask.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncplneox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2juklyurf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2xoswcpbj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqaxutaj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2zctodbbr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2dixvbwxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2hormhntx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2bisbgszd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrtfusog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gt2mviyjywg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2qdbzekft.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2mokxisby.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2jgfeauqp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2csbesghu.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2xwvohxhs.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2ihpovckx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2qaeyhukz.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2eeyahwnn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2zkcffksv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2xnisxklh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2nrupefyn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2tuhntoqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gt2rlwaxaxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2jdxfecxc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emccldhv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gt2lpeegicl.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2seoovhoq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2coarziqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rhabcvpn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2aplkknyl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2yhcazpya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2eoxzxauz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2tpbifctm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2dsdlfqio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2ttmpwdkq.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2gpdsecez.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2goibttsv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvlvqept.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2duvkmwho.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2ueaskluv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pooboocc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2fdnyexsu.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2fcpcuiis.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2jtzbheie.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2isuuyzls.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2rfnsgxef.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2tfscmvon.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2fzpsraii.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2mwczonvw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2vyklocxr.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2oolwlifr.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2iyweltxg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2pjplizzs.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gt2bwtderea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2wfeaevqf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2xctblmnl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gt2cjcuwrmo.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gt2earvehpa.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2rsujjxjv.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2kpexxvru.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmslyrzz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2ljuvfrkw.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2uzvnzyzp.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2czztokqb.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2azgxiuub.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2telqexjz.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2pequvowe.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2sgjayyri.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2zjvjxhnf.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gt2txybnwdy.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2ttelmgvo.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2ibgniswd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2ebpbftnt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2jmjmeglr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2whikjbur.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2gsurewws.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2elchyhfm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2mzzktqbk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2etxffntq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gt2cdcygbgy.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gt2efdgjewi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqonmdyb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gt2oqjshozs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gt2nxktbgpg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gt2boeqbkto.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2rxxkobww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gt2qokezyjh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gt2bmivittt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gt2ghprgjww.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gt2wtbletqj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gt2qkhvmytr.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2wlnxgfzj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqwfvats.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2oqxjalng.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2arulghxg.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2ufaxdpjk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gt2ucslswqp.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2pdlkmevr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwgrnosf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2zhqytllh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gt2wvtycule.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2gnzumcpx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2cqsytcya.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2evbwywbb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2uxpyoxcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2gsvjvlzb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2qglgoxex.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dbrlpxvm.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2yskdzvlj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmxfjfzp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xatyyrtm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gt2ejtwveqs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2pdwduzfl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2noygnqgi.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2azfisgva.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2jdtvnfhf.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gt2dluxwtqf.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gt2nzmuevoa.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gt2ryiitnrq.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2wapwfbnb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gt2lzbpvsyc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2hgvcxeri.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2lghqnmjg.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2lkfipbla.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gt2ghfwqmah.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2xjzctxkm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gt2briwuxze.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gt2ijvlumhb.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gt2trxkfipv.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2vwmnreep.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2roxlvulw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gt2xmulhbwv.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2cznbklcu.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2uykbdqys.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2tmfifyrg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2zaqpjuan.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmjbzrxb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdqcaoy.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gt2pbwzutnz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gt2uydeuvjl.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2dqhhxhvo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mwcqugky.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikdcmifi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gt2cbrmaaay.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2obsanpqf.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2jnualjdz.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gt2ndvxacar.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imlkwwmz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2sspxcecd.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2aehhzzzm.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zesbpidb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2ihestlch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2bxckxjlc.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2aobdwxzk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2ajfingpc.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2xqudozmz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gt2dlhjkfgb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2vdztcypx.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2shtehzfl.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2kjameeml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2igakbroe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gt2wsohypmk.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gt2nqohnffh.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gt2cmnrkoyi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2plmlwjwe.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2lnuhifaf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ptyzgtbj.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnoiuubs.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2blcjccno.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2ycnfiyip.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2fcckopoc.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2weudasvf.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2ttxcecce.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwujvcep.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gt2smlmptez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gt2rpmjvzcm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2ceovmvzj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gt2gonmomnh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gt2swmuhmrf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gt2qzigxpyo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2gyglgfjt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2qqzcmijf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggvzhmgw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2ikwbdmmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcpyxjxw.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anpizmdz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2weiwvvxy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2afmyfspf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2mbrasqyd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2hjwfsgek.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbdwdmig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2nxuqtfcy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gt2rrvwywsu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2vqzenxge.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quzpixoj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2mhaaseha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2maprmrli.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2gfibupgd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2elvzpbun.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2rfsxbhzq.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdorhdrx.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2ntlxjudj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxcsegsh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gt2zrvpxfha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gt2vsxhnnph.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gt2umvrqmdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gt2thgrvhuk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2hwkjkmam.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyhukxr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2zatuyyus.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gt2usnimvfi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgsznay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gt2xlpeokyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gt2ikrzldyc.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gosczvdn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gt2oxbsxwzl.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2jgrgmjao.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2khfmkotj.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wkdfumsm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flmldtgp.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2mrkjmnwq.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gt2bzirgpcm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gt2rnmybhor.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2zhvrpjgp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2xvsgndzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slhzipvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gt2rszgcypg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2ajmmlnxh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2vhozqdft.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2idcehasi.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2lbwssudb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkowrlww.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ubllwpns.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gt2jepqrjnq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2qjwpdrar.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gt2thfszgrv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gt2nunpvmug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gt2oiolxpbr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jyykryra.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyvdrjdq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amwpudhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnilyef.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gt2ciugwskz.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2szexzqnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2nvmctgat.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2ltxhqtng.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2oogtrywp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gt2qemsjjkp.html

);
来源：http://dali.wangdashe.top/Article/details/gt2tfmgczlf.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2koilftwk.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gt2qgtgzzaj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2fkfexhhz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhmnnyp.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gt2bnxwnyuc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gt2zabhvvpx.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2lohmqdiv.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gt2shwmtnej.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cojkswdi.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gt2opjrumfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gt2kdghvcxc.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2qhfainuy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gt2ciksuslw.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gt2gbmociru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gt2jiuqohtv.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gt2rzfehnvr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2brwflwqz.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2jbsjvehz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2rqzzrefq.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdionbzi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2demyhijw.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gt2ubhmcrkk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2bbkfeopt.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2rrytqepx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2ljmdtfqp.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gt2dzddcfur.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2totqnvsx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2qpqwdrft.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gt2licloazx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2rmyjpuqc.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suawchjg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2dcngyqdj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjzvsbbo.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gt2ilfaxmxc.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2obqebcvu.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2pxkztdxw.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2iezdxapx.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gt2dunsjvcn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2gbnxvmil.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljuzpevu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2tjxsicuj.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gt2snjtcjvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhalfdee.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2ljmnfmeu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2invtiflk.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gt2yggsrwuu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gt2qrewdnwm.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gt2vxewixzl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gt2qsdwddoo.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gt2iqvbunsa.html


<!-- 参考信息 -->