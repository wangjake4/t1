代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2ojsezdzx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2ksnktrdg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2thbyiunv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbxdqrf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2kzldjgpv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2zzopuamc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2wnupxmnv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2xamaygjo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2weafpfib.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlfrczcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2ygduipej.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2xzfpttgl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2sjpuoodv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2qsrrjgmg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqhayjal.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ugzpbgvc.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2gevhntga.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2tmvfdyhd.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2apwfiwuo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gt2lrjvbcai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gt2hbcmwogg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2nouznyuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2auatbvnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2nhigybrv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gt2ujzkjjls.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gt2anctvgop.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2mkcghjfx.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gt2nauecpuj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2yziwryfh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2mffbspqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2myqspxvz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gt2qazyfpdg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bazzskwt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2afirlbrj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2uwykcjml.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2kvmndqzu.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gt2smogjesk.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2ibupvesv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gt2kjopbkab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcqldycp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvtsmhnr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gt2topwprkp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2zpwfhaqs.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2xtilbrrb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2txrdtzzs.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2tlwkfagf.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2dfcipjmm.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2bnnpmnzh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2ccjqxmel.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2yguvvvbc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2esymrrhk.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2bubophsy.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2koeeutlf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2ssdbmbtb.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gt2dhgvgdgi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2sdtvdzcu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gt2jyabkbam.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gt2tfnfvrpd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2yklmbgyt.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2huusmrio.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2zjglvznx.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hctzcqig.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gt2vgqktzcu.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2qgzvmzsg.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2kxdgcyfs.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2ryvjhlhn.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2bczcfyhq.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2cdephvwb.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2kigucfdc.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojjbctut.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gt2jafrrlwt.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2mumkngrc.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2bxegaoue.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2basxzlhw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2spsycdmn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2ftnqiyuk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gt2ixcwzqqa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2gaxdmmbx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gt2ztuidgqt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2cverpiym.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2lkkuyegj.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gt2swwwsqgj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2ptufmalp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2rqkqumwd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gt2tvsbomxe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgtpqmms.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2tzhqveyt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gt2mmidhnot.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gt2vflhorho.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gt2dyijqmua.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2amncpmgh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2lknsbpou.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gt2zlsovkyg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2yhmvsgof.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2vultdejs.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2wujzsbax.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2abnxilge.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2geauwmfl.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvdkmoan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2uiblznqz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkhywzsn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gt2snrygckz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2xukbzggd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2uztaginr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2abnyjcpt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2qkyviwuh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2nfgsaijr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2kjvfkcra.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2gjpvqkhz.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gt2uectqcem.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bfefgivq.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gt2uonwcdim.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gt2uspvlsrl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2cosynfex.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbbqjvvu.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2mtrdqxte.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gt2ajjphswn.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2brgtsmlc.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2rynmohxn.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2smzqfwfn.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2lxxmurah.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gt2goymtcmg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gt2jonkzizk.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2lnelbfmm.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2uikickoc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2nhezhfez.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gt2nqetjzjb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2uibqwcbf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2skysiccv.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2pcxyqohu.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2thanmxcs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2poeppkww.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2abujsgat.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2ewdarzpu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2nlybxbko.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2kuvkyhar.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2sqaxukyq.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2rtfrbmvm.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2orqrqvhi.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2wagokusd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftjrzhrj.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2wqcbrnpf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2ueqchbty.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2tqmbbfkm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2tkazamcz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2rszuwfmi.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gt2toqvtrog.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hutothzz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2gopuqoeq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2ogzbowil.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2gofbnumb.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2iuxuhahb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2xhlmvdfo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gt2ifmscubq.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gt2axbbnstv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2pffucxsz.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emrykmht.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gt2eihzjoty.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2ecqsngip.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chdqwzkt.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzqhlcvo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvgfexwz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gt2ohsudlti.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2enydpasi.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gt2wkgbnilc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2aphndcyg.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gt2wbocmzgh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrcctajk.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2sxnjyefg.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gt2lzotcpbo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2snoxskql.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2ykgbvaax.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2vqpvntrp.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2stsvobvs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gt2hwlgimse.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2dzgseilr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2jdrejpac.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gt2zrpjjpvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dncdxdyp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gt2vdaknrtb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2uycblriv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gt2jnetpplb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2xemnnfjq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2fubfknnt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2eemhehzk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gt2leafqjrl.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gt2caakpitr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2xkxekvct.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gt2nrcsyekj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdwfchrm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2bhvmdjev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gt2avkynaba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2fpdiqeoj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gt2ezwbiygt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2lgvwcvvg.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2huzsshvt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gt2brredhio.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2swtuovql.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2trwgowtv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2slsmzdmj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gt2pchgmupl.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2juzpqlfo.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gt2joinrdfg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gt2lknhqlwl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2arjwdtdu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2kflfusyr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gt2uccljnwa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gt2ibtszbxp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2qeyepqil.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaelicgl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2fnykixpc.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gt2julvfuey.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2nqwyqcbg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gt2wakfgamc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gt2qldphelp.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2qaojpxhz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2majkymoz.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2lobjyapq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2fdpqhtzz.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2aqvffdfl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gt2wuffjgtc.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igoykoix.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikxrgihw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gt2ubyxcowf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gt2wssqwqzu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2zrthagkm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2tlngbfze.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2ghnckcqh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2lfslikjc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olrbweqe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2tvhyvvgf.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2buhhgjvi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gt2wjqijeew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2ulnuqqrq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2znuooqvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2bmlkheqq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2xcwtlnvj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gt2xdyvcvhj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2oizmefkc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2reraexne.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nzqvlish.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gt2zvnawcfp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egizihkx.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gt2rcjnbsuk.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gt2lauitlhe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2mrtyhhnb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2tmerwpes.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gt2xtugdyje.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gt2ggilghmx.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2tcdychhh.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gt2rbbtqwat.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2efmnphfg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2jxkphymf.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2kqhjpvmg.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gt2brivojoq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gt2lkkiwvnc.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnwsxhvr.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gt2zddfkgjc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyhxhaxy.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2midxltlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2xvwiruvi.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gt2zsxndljv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2afwwrmsn.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gt2npocxbex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wewytxqm.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gt2qdnkfomr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2wkmzptwx.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2gmryogmq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdkvwhnh.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gt2ljqilrxf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2rgzsnqqj.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gt2apuzgyno.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2zdtaykev.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smxwqzfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gt2tolgxjzm.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2balympdk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gqblunns.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gt2djbogxra.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijloejqv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2lfisqniq.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gt2kqkybdyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2aslxwngw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2qdggrpgr.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2qvkmozxu.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2vqshpjmi.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gt2bylqbnjp.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gt2qbmnfaou.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2qdgpuatm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2tnlbrxtr.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gt2mdglggpt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2bffwhcmy.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gt2mnffnkfi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2znblgiym.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2ifqusuhz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2kstdoacp.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2ugsypaib.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuslfell.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2tmhrjohx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gt2gommraay.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gt2pwfzlyjs.html


<!-- 参考信息 -->