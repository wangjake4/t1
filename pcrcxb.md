代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvrfrqsy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2scvjzwoi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gt2brhlydxp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahswhcfs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2uozbczkr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2mjbsnntt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2tgfybzmt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yotfxhjf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2qazbmuim.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gt2zppmeibr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2habarhuf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2jdcmodlr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2glxwdnrv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztzqzrex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2evthvdmw.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrhwdsst.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2flslpdry.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wllskjmq.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2oomjgeki.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2bstqwqie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2hhbdasvm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2mowruvfr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2hhvunstv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2qhfvfjfq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2rqwrsqeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gt2jsmtuwda.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gt2yxjtabqe.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gt2jvfwrqtc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2axfmqudt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2uwkvyoip.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2drqurwxk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2ycgtyejp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2akafihan.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gt2xedaeowi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgulqasw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rikacits.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2ruukuwxl.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2rpnxuskp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2pmjxhrua.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2zqopqzyo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2kdduwsln.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2gikyuytg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2unlfytkl.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uppxnlkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2ghzxfdkg.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gt2xvawjtyq.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2gvvrblyf.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztzcoldu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2ueznmrcl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2roksudfz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2efaskrhf.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2egspawgh.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2abdsjplt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhsftnbc.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2quceasez.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2xdlcigpu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2nctklxwh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gt2mylsypxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpendfra.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2kwwahugm.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2ilycnnou.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gt2jdhcgjjt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gt2crmeogdw.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gt2khpkjgvm.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2otvgexsv.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2edejkjnv.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2wpxoyteh.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2yhxycliv.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2jboddiip.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2xezkpeby.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gt2citwsuvr.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2vsqraudp.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2flmbvfzg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2enlcazzi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2bgphvwvi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2itebzrtm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdzzsuad.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2jzrlzeax.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gt2xhrnemhi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2ceuvyvcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2agphxsfr.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmapqvvb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gt2gvlvwdry.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gt2srndzaei.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2holtsurr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2bxehvaiy.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gt2eycekemb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gt2wqhxzule.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2qkrwrvbb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2exqhfjnr.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gt2embngwcd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjmkzjvz.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2rkugswoz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2sikymtgf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2ycfehoeh.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2krbfdhgn.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2zxnnzqsj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2peudeueg.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2mhqqsulb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2bhichlnc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2szwrnzri.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2btaiomje.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2qaptuvlr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2mmfwuhmb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2dfgluwag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2jmbxciny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2iumlbvuv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2cajsgwqt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2emfcblzw.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gt2kyaqbkvm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ehyhddiw.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfctnpzb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gt2ulmphvox.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gt2skvluqmm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gt2grtlrxca.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2pfjbrtay.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2rpshwpqm.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2yxsctkry.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2atdqydph.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkxokwrw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrqijjm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gt2omayfzpn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2zebzpqmx.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiywlmii.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2qofjtqiw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsilytzl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2wpzvhuzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2cqedzttq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2kugokkxr.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2sfrfripl.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gt2gocozfyt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2ysawvfbo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gt2rrepwhki.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2jlrewzyg.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2smzttyhz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2suponalm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfpdwfqs.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2ylodamej.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2whqxqrqu.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnxgbdjo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgxsewch.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2cxuysxjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2hxuuvrum.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gt2hypwyszq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gt2eseeimmd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdxuaxwx.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ijlvbecn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2kxvgqcsd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2ovmfdopw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2lqhqqbyg.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtgmoqhj.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2yxzdyyki.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gt2oothfbrd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2yxyymjoi.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2tlcxvawn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2vdmbumkr.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gt2psdrcvoi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gt2cyxgdijo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcqneuhj.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2bbwdlwxy.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2lsvprvqr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2khqecbpg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcxwgpbt.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgluokhm.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2voxlwnya.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ksyyhrwm.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2ppcemdeo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ofuksvue.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gt2gpsnomnk.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gt2zczvvcis.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2vyhqysvm.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2yoohwhxz.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2hehsrcff.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2yknrdmhj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2kiqtlxvr.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gt2qannxuju.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2ynqekizg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnmcctyi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gt2jfexjvea.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xerzugxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2ugmutomi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2vhpqatjw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2pkwashsc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gt2fmuyhndj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gt2wodtozuy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thgdedeh.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gt2hpvmyuxp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gt2wygjsrux.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gt2jibxcapj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2joljlwns.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2gzfxqkkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gt2fxomovgn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gt2kmhmqmmo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwzpvmmn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcufemrg.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gt2lxyocwvk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2yagmteas.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2ukzjtkxp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2ravhyvvo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2vshcygsj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2srinbnpb.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gt2ciqkaxos.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2ihujtbns.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2dmwftngp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2yxjwtdoc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2lekrbkun.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2mzapomfu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gt2ctfputcu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2rfmvbdwp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gt2cjfqpewm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2ivgoibte.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2fzxsjwwf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2gfyyvkaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gt2kkgucbxl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2euntavmb.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vcswijma.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gt2malmyptk.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gt2fcsmxalz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2jnamawqc.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2gibjodcz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2yljngnet.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gt2kzmzwump.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2igqxyqis.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2hlwgcbab.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gt2fzznarcl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enybdsdm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2oiemmcsy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmtndwnu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gt2xhoxlumv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjtxskjt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gt2zbwygqxi.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gt2orydoahw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gt2nlkgujzu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gt2keofldnn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2kwbpyukn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvwrwmgq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynkqnmeb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2jfrkkfsz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2ymrekpyw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2ddxibjta.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2sbhhgokb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2jpncodmi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hwizuixc.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2gtlllanq.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2frfgqdbn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2szwhqthp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2vjryduhp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gt2hxtzlrdf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gt2eiyoqxgf.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2twyjhmga.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gt2xdxizxwi.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2jsmwielw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2lzetvrhg.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzuywiiu.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2twdqfhnz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piurefyu.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2qjavvppd.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2ccyxwqox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2rwaaaiwi.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2qaxbbogt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2jmxixvaw.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gt2grgergzj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gt2wefifdoi.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gt2yrbtatsy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2ydpbhocz.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2comvixha.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gt2ehupbdem.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2cyzomagf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2qplhlcuh.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2gqxisugd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2sqaxontu.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2wepqpmqv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2wsbtqits.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gt2kobifmkv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2ancjizwb.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2cjphohne.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2oyqglhxq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2qjqzkhnw.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gt2mhereugi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2cjqfqxek.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gt2hpaveipy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2hclyraga.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gt2rijdoqda.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2mybgagsy.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2qvlbjphm.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2mmipjkfx.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2dzcnucwz.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2wanhcyle.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2woydruhk.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2rdfjkrmt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gt2yqjnpbna.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2vwcjvlfd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2qqvqcnkt.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gt2ojiiscfh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2trtqkpig.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpeikmds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2pqdpzkbx.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2atqlkhnt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2dotxnxfi.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gt2nyflvhlg.html


<!-- 参考信息 -->