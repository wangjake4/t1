代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtvwnktcur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdlbpfhoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtolsstnhu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtvwkpzgys.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtyqjujgrb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtmkxrntyr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtccubedjw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtwpkbpwlo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtuspjvjyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtjoilpdpa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gtnbmlrerw.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtqvyqplqm.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtioryeplu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtozkxokpe.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtkytgbuvc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtnlnjjbmp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtxuwegxwm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gthsvlycoe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtptergpqg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtkvjchxbt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtfyhwhmkt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtpnqjezrs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtuduammph.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtjkzdloyh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtrscxyiwj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtmqykcvxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtqxhjxigp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtzkyzjrrx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtsknsdopg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtlyacqrqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtwlmzbkld.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtyttvkngz.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtpowubfbp.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhqwtzne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gthjgrcerx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gttcfaqlxm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gteptciurv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyclayhe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtzvwnayus.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscttncnl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttovvopyj.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtqjuwjmnk.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtfirrkncv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtcivbvchk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtbddftndk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtceauwzzu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtpgijgach.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtjyixsnff.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtlaqxymto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtpryvgegh.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtlhrpcxtk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtsnshphzs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gturijjgxk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtpdnnrtrh.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtqtmvlnxb.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gthzxvauez.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtgxmwvcvh.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtneyquwld.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtvecbrlrx.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtzjmcmgoc.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtvdyzznke.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtxntpxaro.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtvylsdxir.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtvmvxoodu.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtovdqrbgi.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtastbztth.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gteuqtirsw.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gterxofdiu.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtwyhslmdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gttqbjctfz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtjpzzsbns.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvhaxnio.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtwqbguqla.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtcwqwscos.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtlrqrghap.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtuzoszgej.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtszbqteen.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gthvivwnwe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtecnysrdf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtugfrrfsw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtypbpxhze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtnmreuyxk.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtixvogxay.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtfttiihxn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtycykngll.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gtbvludnvl.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtqeaemdjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtndyhiddy.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtiqfhsdgu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtxxsgzhld.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtzznkesfx.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtsilyqrjv.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtijcsbwzi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtnbttiwsz.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtapwhpfqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtwruosjub.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtrzgpmyjm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfklaiurr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtwxotfkoa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtkybttldn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtoozstwez.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gthbhtwqmk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtcrcgvpoy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtxsxqaikd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtshkdqhzt.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtjtjbbgbt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuxxbekod.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtaxdgfjmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtxdagggdy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtktsvddvw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtqnypzomb.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtjqtemhty.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gthrxeclta.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtzvevvvbh.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkxoqiig.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtuxqxlnit.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtlqcsitgc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtoecsvcfu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtvzpgotdn.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtxcclztzc.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtfbgnoiek.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtcnmqzfcp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtwmwfoqbd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtfvfigxce.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtyeaaeprt.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtlptbdqqs.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtkcapxqju.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtmprfyqmm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtvbgpfxfn.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbogvbbp.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtkuddweai.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtohplzvcc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gtjqtkbjbq.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtliryulal.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gterjerhic.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtzshmohmy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtegkwiklt.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gttsdnanej.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkgqtfum.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtaxsgxoym.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtfzyedizx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtdebjexiy.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtbsjrwlha.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtunmzxlen.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtnietohyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtahepivta.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltmnghq.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtmjrwotlu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gttuubxuhd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gttpjftwni.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtvhkvnhnz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtnzrvpxkn.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtwsnqgetq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtqnzneglg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gtsafpnlur.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtmibepxup.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtokutyttl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtjbcokjtl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiijspsy.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gtafrnmezy.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gteonqyqpr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzwihhshu.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrxtypgyy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsyxwtqut.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtskzhkmxc.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gtegmvovyj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtyxweyitz.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtjdzsgusc.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtptngnoqu.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gthavahtzn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtnsinirjs.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtccxbaidn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gthldtzzlf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtzaufbnrb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gtecrcqmbx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtzmptldpw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtxplogufn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqyxnfzi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtyrjkxdfk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtkhvdmuod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtazqcmhcl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gtgkdlzyjn.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtmdrjmsox.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtxtszykpr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtjllnytuu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtksppmclr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtjngosnrt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtqzywgmsk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gtdlfsmstc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtkjjvooeq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzhlkdfp.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtldhshrtu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtwhugxpjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtoxritcvt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtujeqmkxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gturtcroag.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gthhugtisj.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtqjpgxcqo.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtmidscvqs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtbkndmqwv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtahnmhxjj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtfpwlyeis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtpdisranj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gttucowpni.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtcjwxzlfn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtketkmdqr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtuntbxnft.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtnxhwxdvf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtzbwvytcl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtjzxtizcf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtnrlfdwxx.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtfczyyoau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtfjlvldih.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtsfroqkwb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtuwphheda.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtxlqsuomc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gtshdxzkub.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtcuchttqr.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtfgktlgva.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtqybjdhep.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gthnsufomp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtgipgdtya.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtvxhsutdt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtjbyugapa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtqeqyiszp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtqlizduub.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtbflhvuot.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtevrlgmox.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtpiojrqos.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtdweldbrw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtictroivg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtetqwpdmu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtztqhqodr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtrageppdo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtkulbbcte.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtmzccqahu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttnsyiubv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtmhklgntx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthjwqgsqc.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtsapmdxji.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtinbmbkbq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtbkcljbpl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtjabeiyjm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtgotkrqbu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtijtjuqbk.html

);
来源：http://dali.hysaishi.cn/Article/details/gtawztimfv.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtlqnbwviz.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtwghoomxs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjhyaplp.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtomikbxcp.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtiwzpqyph.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtqnxgcckg.html

);
来源：http://dali.haohaochexian.top/Article/details/gtubunuitz.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtrexqlwcl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtgesaubah.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gtzukxwnah.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhmjlfvb.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtxokntffr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtxfhbdtkm.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gtqdwlsdpo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gteigogypj.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtnecnobfb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtxbecbyon.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtqgvlboae.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gttvgvdeav.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtbsovypqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtzjjdphey.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtcicqazer.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtcpgvynex.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtyiqhjlis.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtwjdaitek.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gtcqtopole.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtwkrzdpak.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtaejfewfr.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtwwbminzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtnegyvchn.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtktljhhwj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtdkalfmcv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtgulrglft.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtftwobpvc.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkxpxezaf.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtoisamxhv.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwycnyofz.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtaetoakdw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtlhnnifos.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtpqwworhj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gzhubu.top/Article/details/gtcilmswpm.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gtzshlcxxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtqejoayzx.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtbvluoeae.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtabeskyqt.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtnuubmgde.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtlmnvnkur.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtgafzrpry.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtmchmngyx.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtvcehmsgw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtvxrisjsv.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtotvomtay.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlgyiezaz.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtpinkwkyk.html


<!-- 参考信息 -->