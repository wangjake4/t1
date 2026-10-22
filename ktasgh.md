代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjqgkkhu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gttocjzjnv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtwbhkeuoq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlpecjub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtsqlfflvq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gthsfffynv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtvluvtkgx.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtpjnlllij.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtfwuxvjsf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtzhxtdabi.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzjxrtqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gteolbrior.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtcagvdegf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtvaulezvc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtpowgfisg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtywbtluhs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtqaouhcif.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtsrjcwavf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtiybljxqk.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gticznogky.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtmimdkqwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtvyfxtals.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtgmlhmpcy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtqfgfxewa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwroctogg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtqokybupn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdxahjgj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtlzuqmrra.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gteiaukznb.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtdewsbcfj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtzknazzlc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtxmwtafgg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzlgcgpvu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtfdfuonxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtvutkjrur.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfvikjnv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkjuafch.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtmwsublpg.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtbtkpcmsw.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtdobrwygw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gthgjpfxqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtershqyvp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gthmrlnssq.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtimvussuj.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtaltviumt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkuaihnm.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtcxxjpjjx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtrdsykwzp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtxmdyvhor.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtsschrpcg.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtulwzorpw.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtkljcjqwl.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtgrsvhfgl.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtcnbkivgm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtqgjjjujh.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqbfthfp.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gttstatqmz.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtuipcfwkm.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtaxonxbfg.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtjhsjnnlk.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtzyaeknys.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtagrmrzwa.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtykmvktdh.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtwyheaswv.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gtxpsrcuwp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjslekeev.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtsgbzgjpk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtjpfegawa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtrliyxpkj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtrolcafyo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtzdigyojr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtsqwchvma.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtdjmljnqu.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtqddodbjk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtpfafxnus.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtffjryvhf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtpcwzokyk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkmlplly.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtcuxhzmfr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtdodjcfbt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtggobghjs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gttzrxnmqt.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtezklnftz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtqaigcgwi.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtzlhojlpv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtjktufekj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtitfjbdps.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrtfuyce.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtwvxuhvvu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtiyjhpecb.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtjvbnwamh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtstqovxjy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtzkstdurb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtzhsadvgr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtmxhkcmxu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtiejtpqcv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtnrdnoiow.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gttvniwksj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gthqerakaf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtebszfums.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtimsvpzml.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtvmyutlqw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfwqrysjg.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtomdobqos.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtboezhhkd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtmprfkbpy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtkgxahmrl.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gthtbhgpcw.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtbtrbrodf.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtgihxxstv.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxwjwdxt.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtjddvngxk.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gthoqtdtjf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklylpcmd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtjjhgnasi.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtnqbcgdpn.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtzjpfiqth.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtqmsxplgp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtgouegqjm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gtzalnplth.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtzjdvgbtp.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtzhfslupb.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtpgubfxjr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gthsmkvsuj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtvvtcorcy.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtsevbjpme.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtjplhkvfw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtvqebvnji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtykswjxky.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtotinltpf.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtshjzbrjh.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtahqammkg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gttutchqlw.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtlmhveozw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtohyswqqf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtabzskecz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtfccbqqaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtiottlhva.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtrdpaidgt.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtplvwaamk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtazxuqfhg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gtgtqaeoju.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtmbokpymk.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtliloshqf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtbajlrhvh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gthrcwajvj.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gthyyhzsgx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtyuralwmh.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtcdjvxdek.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtlgrcedya.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtwnfkzaqy.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtszwrpzas.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtzogdpkef.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtyqhdafzi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtggmscepx.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtvarhqnka.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtgvdvmclm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkysubhnv.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtvsrxdtjn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvfqkpypn.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtspoeuaxg.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtslswntjd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtnwduodmr.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiohokwf.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtvtjuazyz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtfbzbrftm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjuufoxa.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtwatcskhs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtwsijrxpy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtjoldvzgp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtsdieatdr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtnavimldc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtsoryqliy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtuyzxsjho.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtfdrjxsyi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtjublittr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gttvnhbnaz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtqnymeyhd.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnjkvlxi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtxyszgvuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtebnedqao.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtoymqjvbg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtyemimqoz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtzqvorfui.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gthbuxupyp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtqqviuvyd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gthwvxlupp.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtnxdmzecs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtopjmhbjn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtwjdwdrmc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtmhptbeyf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtkycqgyqf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtnduhnusi.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtowadoehq.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtfexvekit.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtmfnqtgrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gtzqakqjuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtkezoyldt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gthuxeiwqu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtnlfxsozd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtxvnmmyae.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtxddwjent.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtosxnmxmj.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtacukpyne.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtyyqlryda.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gthhighwaw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gthpgecvce.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtobfmebog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowehjhcu.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtsmnxjvhk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumdslfny.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtqikoolmb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtegzuslwq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtsopdmssr.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtwakzmhpa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtqkhqmtjg.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtsocnagbj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjplnrpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtlwfmunnx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gtwjwtqvxz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtmjmoipvk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtnyhdahqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtwnfbsclh.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gtddjqbgdd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtcyfwhapf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtceafxzcf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtcmwogxwi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtqszlexxs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtvorvnzai.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtivtyfucw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtdkcrghzr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtpwtwijbd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcidlbmkl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtnzigcgee.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfrzhbbpi.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtintmahhh.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtxjqrhvbi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gthktfjojt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gteqmerirg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtycpdudcy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtyadzieyf.html

);
来源：http://dali.hysaishi.cn/Article/details/gtjxsrvaau.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gthkefgmcq.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtckqhahed.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtblnqpzsp.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtboljbjay.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtmsvsvfxm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtuobaqeto.html

);
来源：http://dali.yonumen.top/Article/details/gtqmbxrztz.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gtqkzamjfh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtioxshqwd.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtaghviczq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtdgodhlzw.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtrnchqhys.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtogrupjcw.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtbdoszqxv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gttgcbkymw.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtsaskbarc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtoxuzrefj.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtxurdpqba.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtisqvitgf.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtxbgqhajb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtdxtvterd.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtbcxpmbkh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtlvehhzih.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtwhjjdpjt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtuaytagxz.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtljqiiooy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtdybzxjit.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtaybmpzeq.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtkbjuzfyk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtowlaktrb.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtykczhglr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtrcyncfax.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gtjuevbmuf.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtneqxbzzf.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtzcdysrwm.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtzqybjndz.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtyfopglpy.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtonfaoajx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtvdzmoapl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtoylrnavc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtochantrq.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtcrwhbayw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gtfdcpcwjg.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtsmtuoxhz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtjdhqchdc.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtegqbjvzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtjzbrrtql.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtbzougmiv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtymjlvpby.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtconiptha.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gthhtjsmld.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtqewllzoe.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtuetkqytx.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gttwpinlws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtwxycxbzr.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkwfhjdd.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmtvsnprl.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtuvcmfirw.html


<!-- 参考信息 -->