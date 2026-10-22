代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtkjjidqfd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gthduropsn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gthjhetfba.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtljjqamtc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtwjdqmmzh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gttacozhzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtesjrixlp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtzaazyybs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtqypzuzxo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtjmdrccaz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtpxbsortz.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtnvazltet.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtmkskwynj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtmnlarinj.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtlcjzorwg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gttevlcgoa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gthfrzdgcy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtwohcqhju.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtabvwckom.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtbsakbmzm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtrgidlmrb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtglpmmbsg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gtmlwanbtj.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtsxqvmhyk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtntxwfdyf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtunapsrct.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtpyiqoyce.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtojkqdtwp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtgnvrgoyq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gtrzvhpolr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtapmngpfn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtwjftmrfh.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtyeemaxii.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtvzzbrqoy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtlpuhxowg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtulpvnbfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtnqjxdqqq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtsvfwhxox.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtxdchljfq.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtpucodhih.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtqjecyjjb.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsnvsbpg.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtsujuvvjx.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gttxojrchk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtphjqomsb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gthxfmljgl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtzzvzuefg.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtcmtrugxl.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtfuwtzzvb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtfoiclyaj.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtmkarbdwg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtfdksxcyo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtfedwjrux.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtxaackcta.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gthzwnxejz.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtbysxhhen.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtbfascghq.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtjpkaexac.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtgndjyuda.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtuylwbwkg.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdsynzhom.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtwrcsyxxk.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtkjnhulit.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtjjbblxmg.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtqfdedagn.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtpqravmea.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbvnphfb.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtkasepfrc.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gthvmxvwcd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtutzkavbh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtafatmuyg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtxskoegpj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtrfnlkulo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtojmeeele.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtkepnvldx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtjoowetof.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gthuitlglv.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtzdkwfzwk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtcoiweohr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtrdvefgzy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoahkvji.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtsyrbvzft.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtozukwuci.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtccocdydt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtsrmxzqtc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gthgwgxsqb.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtlvdnboif.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gthehejftx.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrhjemla.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmtpowrm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtziqwuzoz.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtehprhdjm.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtmqgwepoc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtjrjjaotq.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtlxyzhwnr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtzvtwwgur.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtmvemvoig.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtisksutuo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtiseirvkl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtjrbxjtpc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxfslmrs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtqcscvtcw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtfziznoxu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtsktovdqj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwcnhuofm.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtnzemyiom.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvnvbbejq.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtxfenrfge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtxsamldio.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gttzpxiady.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtbvqhwudx.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtvqibbqdg.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzzgijgi.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtftjfhuuc.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gteecghewx.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtcnlvdfhu.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtoirrdfve.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtssxdgqig.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtyilfaqrx.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtbustnxaq.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtbtftccqr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmebyxlwh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtoiondhnk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtyhsancfz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtrmdnuthy.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gteoollqbh.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtekggajiy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtnjwdcofn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtozbtjlop.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtmbbkszga.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtqssnktkw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtexetyjol.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtflyavqsn.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtrghofshe.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnutttnk.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtcmibpwmh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtotfqpbyl.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtpbhjwjlo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtfytbxawu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtfdcwovma.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtfunxewnl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtjirebwfq.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtpigottin.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtckcurzsc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtugahearm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtbptphbhx.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtpgnveuuq.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtygdaltzq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtkzlldpko.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtqjbkbpyo.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtlouutkhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtrgajasye.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtmnfakuux.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtjjfsoeqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtwdwvawad.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtulinfeph.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtarapvpzf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtviuutlkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtiemcdzyr.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtjwyiqwfl.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtfdjhdcnd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvrkcbcdu.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtnzhvynnw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmwzpulv.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtpweroszz.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtqlzqdkth.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtvlizsxjc.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtuqcewjwd.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtbzhtykar.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtixtylofa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtkzfqilte.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtzhtpjahm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtdyyisjse.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtxwoexlju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtpxwmwgww.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtdgxrelke.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtdbmqrgto.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtluttsjmh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtmllcnvmx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtlxdjpgkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtnstaigis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtxjwdyvjf.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtekqcntvg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gteimkajjs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtexmcmthq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtnzmrjqai.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtdsolplym.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtbgodbkhj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtmpwugvhu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gthfabmujc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtqvfblsba.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtrorblvuo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtbevzjgkg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtmgeseuyv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtcwhktokh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtgqdoxxpm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtwbeiusbr.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtroxjiiui.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtgtnqkcye.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtazjdcnsd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtvrwqfavv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtlchsgrqj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtvkehqgil.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtsggyvtre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtkjqjflbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtsbcfjgfe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtpminqrng.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtwjazlnos.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtvqvgpmel.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtiutdrfkk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtgxhebfuk.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxkeyvph.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtpapdiacc.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtwbbfpdqg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtonblnooy.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtuqbundbt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtlhghewtp.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtflknucyw.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtxgsqfatf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtsyplcazw.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtfvuyierv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtntnuruxl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtfmcslbcw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvtrmmecl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtcmbegfxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtbuwptufx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtskxshbyw.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtlokqagda.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtvuelqvhy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtwobwunpo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtczfgzklp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gthsmnuppp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtwqdncpis.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtpumnypaq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtsyujehob.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtkzothnax.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpqqzolfv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtpksmqtxg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwgmaryte.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtcdlzdwfc.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gthwrwohfg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtrlibjnuz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtgnpiigrg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gttocklvhd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtpyrexweu.html

);
来源：http://dali.yj20258.top/Article/details/gtkhscxspy.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtutvpnvcz.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtfvrarsln.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtjflqohwu.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtxolchixt.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtlzebudcj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtjvlpnqke.html

);
来源：http://dali.gzhubu.top/Article/details/gtcuuwcewv.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtalktclaf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtatbbsmjy.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gturiwkxqz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtuwlvrzbt.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtnkueishw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtfnhovzkg.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtmhuhzqlv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeugxxeu.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtjzpmcxeu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmpqivrqb.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtnfkxajec.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtquibwpsn.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtpozmyrop.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjhmzgmy.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtuxjmpjph.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtvkdlxvub.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gtbtphiuzt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtmbkxanqq.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtnsexrdmh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gtpmukzoat.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmzhlcs.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtoiokuayn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtroqdmxbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gttjqaghvn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gttnfhdqao.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtreeahpou.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtyxeifwpo.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvcvbfsuc.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpvgeomu.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrsqqoujn.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpsetfdz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtvqldckqb.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gtysuiuskm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gtlhtrrjbi.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gtcqrsrnvi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtqvzseucg.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtmdtalngu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtvywbqxtr.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtddxgeqjm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtkucienhf.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtxyotngby.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtmgldsrho.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtgmgfgyfe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtddbpiwhc.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gthodgouxk.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbwdttojq.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtusecpmzb.html


<!-- 参考信息 -->