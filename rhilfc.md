代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtkurpbuvi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrkbbfjjf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtkszsuiyu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtmbeddqnk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmfidhqp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtabwwllao.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtedjueack.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtrufznafh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtamgzraoz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtegxxsyml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtyqehoghe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtgiercpuv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtrrtmglgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtyvdjcdph.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtpjlssqis.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtctersdtx.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtiomfwdvq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtgslxhtzm.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtgvahtcii.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtacqpwklt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtkwuxkntz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtudsiegia.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtoujrfcnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtbivcvrzo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtixeoplly.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtojasrwhn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtdycospzu.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtmfbjhbrw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllbmeoro.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gthfbqqjcg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtyoixtasx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtdbtwxsjr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsgdiqdmv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gttasgirwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovolxany.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtbikeqnpn.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtacdqdtzc.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtzfyvvrla.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtvhlzpsvf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtwkbxmxtd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtxldvpefi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtuptnlzpn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnstckldl.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtrkawytyg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtgrpoukei.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtssbqhsvd.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtemsepnyp.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdeewlvcq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtqodjvzyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtzebuwcmw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtlsjjzszh.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtmfhgkcpj.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtuhermkyo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtkyzldziz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbyfrbxe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtlvkeqcxt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtregkgvss.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtkpkctzje.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtaxbyouye.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtcojansgr.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gthzpredbn.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtgdoliexg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtzuqnfbvu.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtoodtieyv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzmhigcqu.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gteaajeore.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgrwqaah.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtdpnjefat.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtsyhauyls.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtpjrsznpd.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtrhjerksu.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtnobstruf.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtvlfipdwu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtmywyqxkt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtkwlwnupi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtdtprjxsw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtjspgkcmc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtcupeoqli.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gttocfoqlk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtlyuicwcz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtmyfrmpqe.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtleyutxqc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtrdrqrzfp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtscsznwdb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gttmziwebx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubnaswal.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtgraaeqfy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtnhjuthno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtdvbacbco.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtccpkiiuk.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtinlzjyzz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtiyexgsrl.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gtfhrcgpjw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtpfxifgxo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtygehlauu.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtzcszczcp.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtcxophnqv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtfnybnsbu.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtxcnbciek.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtkeuimjgw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtebyinkwq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtquztymsn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtrzqjswmk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtufploank.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gthmvmgkhy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtxxwwbyga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtnmdfdneo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtfvggohxu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrblvxika.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtmroniavb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnjapvlyj.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtukatmzay.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtchfumftd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmomebwfq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtpdvthbxd.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gttnfycarl.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtndagtwnk.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtfbpnnyzk.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtumyvygun.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtntmncylf.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtqquntrzi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtyldlsdyn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtxpwsywgy.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgteasytv.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtelyjwukj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gthxtyxqmc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gteyeucjxo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtoanysmyh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtmvruujjk.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiveqzmtu.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtfvefnexl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtmvabkgvl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtxwwlldlf.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtyswpfdgn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtuyyqbupj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtdqsoepjd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuadohdt.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtxrjodawr.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtdqbtbwnv.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtekugqkuo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gthlcmsvdl.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtmecbwkoj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtmqgdunmb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtjsrvzepb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gttswqibrk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtnvilzhop.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gtzsgjfddq.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtqplwqjmc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtyznexpri.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtzanicedo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtmombdcfi.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtfwwesxxx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtegnmauoo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtnhnnbvkr.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtyevumovz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtwfqpdhhp.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtrdxqwfhp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gtfwaihars.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnybykem.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtnjxeshcc.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtysmvhqel.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtirtfdxun.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtxddftpmk.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtxswshdgf.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtnczbomdr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthfwmdaol.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtjqqeydpn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwpvddcsq.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtbxtyggle.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtlehbakmh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtcyqoyzpb.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtxdtozuop.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtnygfloty.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtudniooes.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtknoipwir.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtklgjgmvi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gtozybssuh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtzrnpimcm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtgvoofmpq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtglfecmoa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtxftqgxxv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtyzdoyeda.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gthelhakwh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtrbshonfc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gttjpejecj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtdvrzngao.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtcocqgrae.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtnztspaen.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtjaytwhag.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtcdtziqbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtgvkpvnlv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtgzikgaff.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtlzhpihwv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtgurbpzoo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtrmayrwkk.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtepnpxpet.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtpxfdbbkw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtvnsdeblu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtgxwuenvn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtmuqmoobz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtlapxejlf.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtuxujyngh.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtgizasmrz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtpsfvmcjt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gthvdqcumy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtaxfmkhyx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtclozcawk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtzofqvvit.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtywwqwutk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgctvdvac.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtnspslboh.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtbqjywfjl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtfydagewl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtmofltncy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtqoezyahk.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgahmabfy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtlrejrmuq.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxlwzjyql.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtrumoeipu.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtlaqwgssj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspyrjcwy.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtwdtqwvzy.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtumxtjctc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gttugbjaxk.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtgxugwqeg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtfqhaadmo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtoyufwwbt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtumtjhhch.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtjluiwnwg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtmflmjsuo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwhjbqbs.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtbsncbddy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtknfwtdym.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtpkkfofer.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtmuppmlvb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyaciqvp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtrxawjyub.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtwwpmrcex.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtmvphaekt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtpcprfape.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcohjfbph.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtnydwvbez.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrkhojfg.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtpqrvfvis.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gttloyfjph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtjmmzvhvn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtnrsseeli.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtjniblrsu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtcpnyuznk.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtietafstq.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtkszgsuea.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtqaqrxhls.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtuimcrgrj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtorvqxwoq.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtpkiwfpif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtekrkzosx.html

);
来源：http://dali.havefunace.top/Article/details/gttzpcwjox.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtdaxzatty.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtmbyzvshh.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtpzwleatx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gttlbldkne.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtjdpjoubb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtedaxazam.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtnntkwxbv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtkumaawfw.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtmbwmxmbj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtfbxdslvx.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtorjymksw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtnecjuhmd.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtryeoqszb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtazxsmuqw.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtazjprwnn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtiqijjlat.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gtacljkeem.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtwdffgtnj.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gttbrgelia.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtgrdtjvzj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtrqopmbvk.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtdfshpckf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtfonzmqni.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtxiwobuvn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtvdaiunlw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtteknbojq.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtnljziufn.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtatuluiun.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtwqwjjbmr.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsxspdfga.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gtzwoszdps.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtwkfifjac.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtrtedxhvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtjtudihof.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtppjgacgt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtcvznstmc.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtbcalohbl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtufnxikpa.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtlizdhtnf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtrsysgasd.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtyclbubzd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtjldvvbjs.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtcjpulvup.html


<!-- 参考信息 -->