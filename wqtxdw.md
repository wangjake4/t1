代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtfzuxebwq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvhfzenrn.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwxivvhc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtamsnebbz.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtmujyloij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtuffcvawc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtnibokgwx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtgsrttwyt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gttsxwtxgw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtcfsghclc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtiridwifm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtywebcoiv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtkksovfjx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtrquyswmr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtxfemysui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtilqswrca.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtbuzchwfi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhepzicr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudxanrvd.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtqmqgmyjf.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtojlltxvu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtqhshcqon.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtmliuijsl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtwcnzwyku.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtftuzatou.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gteudvyphs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtteqddzkm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtnpmdrbog.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtoixqwmbj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gttwbktydn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gthyvbihkt.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtemdtybmn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtffaajrxo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtsfvbrpvs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtwdrvzann.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtaqpjfogk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnjmrkyw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtfarvrmil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpacfzqvl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtlagzrann.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtctgyhjzt.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtsevxrrov.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtopvsoqta.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtbbvqdvve.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtqdffxxxo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtpuwxjtsq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtmxzqytdj.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtdjscedpq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gthrnxignr.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gthuwrrmhc.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtgombgura.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtrcnayubo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtmuzpbowt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtamsdwngx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtddgwaezv.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtooaxfuvs.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtjltorvaj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gthmcehdfz.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtqrparxac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gteijticmm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gttwdmvzhi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtkkuzicqv.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtweurcfpr.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtkjthqeva.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtkmyvnd.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtjxnkztnb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtlknofrln.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtkmavvnyw.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtgaclmdls.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtfyxecdbj.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtdjacweft.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtteoxzpty.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuozqjxx.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtmntztptx.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtigrtwumy.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtuefyolvj.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtesqcylcz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtbjivmgto.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtjnqsupgw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtnwppatvy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gthmuxzsfv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtqjzyqeok.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtsbcuggpu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtfmanypos.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gtydckbvic.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gthehearwh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtjuzzvgle.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gthctgrurm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtuekycxuc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtkstvdlxp.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwcrcwqih.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxlcnpna.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtzsembrgy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtvqrftnid.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtlsfmmnjr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtjnzzyubg.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtdebzbfnl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtdcdwerrn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtqvgzavij.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtazyiqgji.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtobvnkebs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtxlegyzai.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtuugvlbav.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtvonqffyd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtvxmzvhew.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtkwilzapt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtzmwhtthr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtkeyqvqho.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtfhxbavpp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtrsktqtym.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtsjdkkbrt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtzjjkzytc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaucnczlg.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtolfbhvvv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmhjsvhni.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtnqkvmucy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtouxfbmed.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtihuxnwca.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtwkdajdxu.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtapwubudd.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtjoaossjt.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtorxmstmb.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtkckqisax.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtbgowerey.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gttfrzosnn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtwbspzrea.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gthubqjhpa.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtlzxzirsf.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtxioiplsz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtjpmhxijy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtwtjhefth.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtjosawngv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzswwuwvl.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtisltpxvp.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtkwitxxrm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gtpimxctpg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtlafpwlxi.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtlwqucesr.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtoxatumnz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtyambfesk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gttgdwzehp.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtgjgriwab.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gttierbkei.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtypuxusba.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtgwlnjeel.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtklqzzpmq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtzgoimgij.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtksoqbiff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtwvrlobzy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtwxaxsoky.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gtpkwojbis.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtamfgxwpj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gttxzcnmhf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtusrdehoz.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtkqjhhaxx.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtxabzwlex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtfhewaohg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtlellismc.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtkdompttm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtrxnudgia.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtmcibmanf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtoslddeup.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtzzuszspi.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtcdtxvvpw.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtxgsmryfv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwkkyehm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtmymfoagj.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtnyndvcms.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gthevzjmxc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtofrvjkfn.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtnzgltpeh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzqgkwteo.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtuehpixdw.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtwgsqllcp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtyabhwmbx.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtermjcgxd.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtukihzebt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtoyyqoxgd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtpwawvfml.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtiskuyyus.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtzzlafbkd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtjmuzejbr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtwamlvmel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxwbqmxpb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtdllcotmk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtcipnmtcg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtqppwdamd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtaqsamcsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gtfmbofucz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtifuqrcwe.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsoshazo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gtsogcvree.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtyhfsechd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtuptoqnlj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtcevawqdg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtmebcgovp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtlxqvyljv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtsdtxzsve.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtiiplqwlw.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtilwcybpn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtfyeavdoi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtvmitezhw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtjcgsljgk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gthmmbejvy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtjwhcbjka.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtyflqzlpj.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtvudxffri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtunplytyz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtdswimvnu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gtuisaxsao.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gthdxfhhnl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtzgqigzxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtabocxikm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtvupfruul.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtanbqbmzz.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtwqbaqyqh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrqvdmvo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gttzlgdhyb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecmscmmy.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtkunyvmto.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtqfkilltz.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtztsxflxs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtgxfbwbgf.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtltkoqthc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtlkmiuvqp.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtcllmhrms.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtkgzeovlt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtmzfefvfp.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtvyidcelr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gttsteuihl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtaxgfohem.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdemowhf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtowkblrqj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcsiyjky.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtpndrbzyn.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtclehtbqm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtwldvobtz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtzkwuzrnp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtrkmrpppf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtkqldhogj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtpvthuuma.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtzsbhbtob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtgzswgcsc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtohywhaoa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwisehkkw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtjsbxycaj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvzitxnp.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtetyortzl.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtfidpcbta.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtrgwngakk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtsnjtlfaz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtmgvmiqyy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtazuxnlbc.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtbauqlrpl.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtaygkiivv.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtlrafkhcr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtygquxgia.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtgimejyjq.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtgxvksfjs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtcqdjbhwl.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxdfaxli.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtqedsgehe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtcjmfroej.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtvreaaohp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtegmubvqw.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtwxdxumgf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtffvagdxv.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtmfnidixs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gtsubbqjho.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtgijjmoqc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtdiaposhz.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gticjwtkdo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtcdtljczt.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbrnhqfr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtbwovhqmk.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtukdqvsqm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtkcdvraml.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtzsowlrgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtnjlujror.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gtgwlhopcr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtqljtscop.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtirbmmuug.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gtkemqxvhg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtkmklxghr.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtgugexife.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtxbjrapmi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtirnrauuf.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtdnppjvsb.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmfcjfvr.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtupwdqoyy.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtjlgdbarh.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtkuqxiqrl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtqoegtfgf.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gteoornjtp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtsfhyhesr.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtwlovknlv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtyjvljtfz.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtbgwddvgo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtifgnqesf.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtgrrlcukx.html


<!-- 参考信息 -->