代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2pbzyzdry.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2lalcpuke.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2zyahgtve.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2botssszk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2sbxtcphw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2rozhcunh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2efocsgge.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2xmixszsh.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2lovlwwhh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gt2ailrtnux.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kacihpta.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2cpofruxk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2vzoloovf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2pwjnmnwa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2pqaidsto.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2mavkwqqs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pugustwf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2ctguxfnv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uoidgsyw.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gt2ruttkxdn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2eofpmcqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2xiliudtn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2ybvnwpvu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2csgesifm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdurjfav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gt2lckpyqyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heuqtzlh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2dagdamgu.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2ripcdilm.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2dlpvvezf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bysykbtx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2aljjhtal.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcndxxwk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gt2hywvkbyl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gt2bhvpmvxd.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2yjbdqzfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2geopplpt.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pjjlikob.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gt2vdubczod.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2gfdqwadk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2busiyiyj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2prjxghfl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gt2chuppwyr.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gt2jdywvcrd.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2mmaarizj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2astdvhjn.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gt2uqlpwebg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2xmmodbrh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gt2ddowzzad.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gt2hlujthmv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gt2ehugnlfv.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gt2ozsuaoks.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gt2mnotzrms.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gt2uoodwkau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2khxnfots.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2mexwfxkf.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2jiktinel.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2bmltyizy.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2ysccvxfx.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2uqixmopk.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2uwjlwavl.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2hywdygjp.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2wyvganfh.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2rizvypxz.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2ucmdfjhp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2utxcsuck.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2quziulgb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2vmdtbuux.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2alfuwzof.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2fjbcrqjr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2duvkowfy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2pdhyimug.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gt2rfnfmalc.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gt2zvkszbqk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2jotsiyay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibcilgsu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gt2wjhgmwyz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gt2cixeqtda.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gt2ejcfbhoe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2blllhted.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gt2yqkxpoeo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gt2rwkmnhdd.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gt2oamphurq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2nynadtiv.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2amzkfnnj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2mtrfkxgy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfnbmmxs.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2gpiuxave.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2nwsrjizq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2kgvqgvtn.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2pnauigwu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gt2odeohaww.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2evecnsyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gt2jnnocqqw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gt2pmywevdb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2dxomcvcg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2fkupfdqt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2ypdtohav.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2xqbpiqyu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2eyrtixtz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rkpnavwp.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gt2tpcaopfm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2vnjivcrz.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tncgbreh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gt2lkecvvwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gt2uxaeokko.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2zxfvhiuj.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2acuheoke.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gt2dkrqsjju.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gt2taktirch.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gt2pjgfhfix.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2vukfsnsv.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gt2gufcguzy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gt2qvcqvntp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2zeezdrsq.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgyommsb.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2acirclhn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2vhxdykgx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gt2mybhcizt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gt2qqretwcb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gt2fnwhouzx.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gt2mvtokunj.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adouxvbh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2hfinlnsu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2zdismgfr.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2gjgflsot.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2kwxluwhx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2mjplnpwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2xcvrncok.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2dzkyehnm.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gt2mbaaydhz.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2obuugbhq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbmzbyem.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pamaonmj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2yqmnqhti.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gt2fwbhuter.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2ttrltins.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2kbrygiff.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2bkesnnsa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2trdqdnjs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmghiqiw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2jrjtjbqc.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2wmzzfruf.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2anldwtuh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2lcnswupu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gt2hdtfgxpv.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gt2tmqncplv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gt2yiqvbfzn.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2gzpevicy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gt2gtvmhctk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfuvxjmt.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2hcxgoflt.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2vdozwigv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gt2sfeuirpa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2gxakjwrd.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gt2owkiupmg.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gt2mjgaljdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpigveec.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtvgjqwi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uppahhfj.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gt2zhxpluwl.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gt2pzqlugmf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gt2mxiuantw.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2cskvqebl.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2gxgmfzpt.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvzmeglx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gt2mqvweeuh.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2sjaikkhp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2zarvyjzd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2skkdobta.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2yjvibmsm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gt2oucwhlfk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gt2cntacaxp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2ddyblrqx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2pwltcfpu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gt2ffqottts.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gt2ruwxzage.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etmppfsc.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2felppurl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2rxbvcelf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gt2hgcnpoum.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2ayqweuhy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2btuluycr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ykhzmxdg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2osxaclau.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2txrgekrx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gt2alwfxjnb.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2opjdwplo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2bldcczzl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2yhtakwbr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2tpvpfxhd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjubishg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2sqbiwruo.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gt2puujojcw.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gt2lycxmknz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwyfbnfi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2eooasaua.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gt2zyilesef.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2yfcoxxjc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gt2apduqfsd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gt2acnwoiek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gt2lvicbpdv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2pgmzyzru.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2slpgyhbb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gt2tngthbed.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gt2uzskubkp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2ocgnyikk.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2eaeeodpn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gt2evceilzo.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2addsxads.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2litljglo.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2eqidamsz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2jnmkqzki.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zkuhcyqn.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfzpnasj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gt2lzrgtnga.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gt2yvqrrbst.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2aqkjjbxc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2dsquakss.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maywvpui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gt2alggwqed.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2ttzgshbg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2kxmunmvr.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtnlirhy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2huotdamg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2uqlhfmpr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gt2sjpxtksw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2eywdlmto.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2edlqoajg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvdlnzmf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsagnuon.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2qkgrvcit.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wgjvajxn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gt2uxfnylsa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wmceybfu.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gt2hmifdsxl.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gt2eqfzilni.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2ozkpdupk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2axcjchcx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gt2gouglkag.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2nhfvbtwu.html

);
来源：http://dali.cheryme.top/Article/details/gt2eurbnmvo.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2sibjlhmy.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gt2xifpllza.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2vbxhefns.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjiwdeqb.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2nnhuggyq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gt2goxftvbw.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2naxjvdsb.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gt2nqokforo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2desuslma.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fywxxaxo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2gqbltyvy.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gt2tqzfwncz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gt2hlzldtua.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gt2ohrrjalu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2xvimtmek.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2oncgknln.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxncuarq.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2buakyihz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2ytpdnkfy.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gt2rwzzmdfr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uytjznxf.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2mgoxiouc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2xkgxadje.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gt2pwoepmkv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2sgxrsiro.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2xhbjbknp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2lkehrrga.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2mdhsufgs.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2trmidbrq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2dynhpejx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gt2difgtqwg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2bgqppegs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2bmlwsdio.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2bzkmzybl.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2fyzlsnri.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gt2ynpvxtvc.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2egftxuxh.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gt2diotwrqu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2fkpwhyta.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gt2bsiiitcn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2kqxdusxb.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2xvcbdtvv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2raykfyul.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wviquljn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zazohazs.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2ybawnoaw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gt2vdhklxew.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gt2hzaarndw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2pfdpywdy.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2wblrsjgu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qylxycow.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aezybvuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2tvaofaqn.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2cwebfkgd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2lovpmkmk.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2bqvwwvpa.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tncmxkdw.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2nkhtdrpb.html


<!-- 参考信息 -->