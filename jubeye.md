代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtxixfxady.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdsjszgt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtufxemgfc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtawmgfusf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtgshkbkdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtfbsjpcqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtbytqcwnl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtlvnuovlt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gteabfpvjj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtqsfknaxv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtmxocyvgk.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtxpzjnlie.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtwajdtdem.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtxevrsdev.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtanpypbhj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gtxnrcfhgs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gtkoldfueg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtpgmxswrc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gticmvgoxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtyevsduiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtalvbtbtg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtggldctwu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtggoxzshb.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtdgwxzrpe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtryuoqhuq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtdtiywrmz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtyoylzdsa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtozscclrg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtiurzvuuc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtmfftraft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoftawqzc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtnjcgufdc.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtivppfxyu.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtxkcbyypl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtxjtcowpi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtzwxaotpe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtiguxibcy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gttspmxwlp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtanjoaifm.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzoaqjfm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtvssfjyjd.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtboccazhj.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtgrfexige.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtcxffhpgt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtogvasmoe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gteqioamai.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtvtyudruf.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtykaxnkhi.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtjibmsvqj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtmimozmft.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtsemieacg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtaurnbewc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gturbjwtsh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtlfkekicm.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtjbiygjcw.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtnvbqnpjv.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtrdygsqiu.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtsviujkqa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtcvcvzwpb.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtqqeuyqei.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtthdkcvdx.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtfkrdrmwa.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtbmeaxvrg.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtixitadap.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtbygsyktl.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtdxxydwxe.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtameyoqmc.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtcpbkhzvl.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtjtbtygaz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtlnrywncu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtuqtoatfc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtaswgnfql.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtrgkgrviw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtopimbuvy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtfiulluqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtlynutook.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtdizyhnru.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtvyjhiwhd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtyxhawyqx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtzileujys.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtyzdexlfh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtxicplemf.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtpjmsfqrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtmfmczsgj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtydqsseqo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtazunvzjk.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gthpzsptjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtfzfgsnnr.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgxxrhkn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtnuyzkzdy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtouprytfb.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtaodyakoo.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtfdvvpsgl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtgmcdxdlw.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwtqjkeu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtuenodpmk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtihokungh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gttukatlxw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtcmkdgodg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtxinicudm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtxfstwlel.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtjjqmrrus.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtwvisakue.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtnarppuqh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfuonsydv.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtbejgakyt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpugnobsc.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtnoewbwrj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtobjrdqod.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtuukkbgck.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtrsfmugon.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtxykgvmiq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtxwonxdts.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtomeojjnz.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtmrjoqjdk.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtsqvqgzip.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtpnferwiv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtibehcxpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtxhtkwxuq.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtdvowuzqa.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtzmukirqd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtagxmddvm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtkfphktrc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gttgxythcm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtlrwertcf.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtoyyzbqmz.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtvcdfcxoh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtyftkrrhj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtxdeirkig.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtuconctrq.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtflapcuhq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtlkgmxaat.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtrysfadax.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbdijowxb.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtmszwowxc.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtnqszbhfv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gterzvndbt.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtjvvtzyvp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtarlataoz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtqsmbgevm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gttqkclpon.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtacrklgws.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtfzvjhaoi.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtgfpzmxsb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gttzxzbuwq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtgytpkowl.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtotuqhyrv.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gthdflfggt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtnmlnisey.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtlddjlpti.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtcrpuyobk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gtlgqcoeua.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtbglzezrt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtkvzsxqui.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtwlmretyk.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gthzwwwbqd.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtspoalypd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtbknagzzy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtvltuhnzb.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtfyhfkowq.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtjppqjdnc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbpnxnmla.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtebdixfqu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyyrgrqro.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtnnykjdoh.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtwayqkkef.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtsmqhwfyo.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtkcvkwacr.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtkhydtjpl.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtwidtrqfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gtqgtoiwon.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gtjzodjfyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gttblvibsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtdgomeulh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtwcvmcurk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtmjwzimpl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtzgqluqqt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtzyokovrl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtamzimjjx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtiiejubbr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtleerbfsl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtxwouzkjy.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gthstuwotw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtqjofmjrn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtydxfnkbf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtuqdqywas.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtghylsvqk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtqgjsdnqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtbvimvsmm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtiknyqfro.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gtpxyyvknx.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqzlavxj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtkmvzdwrn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtsfuztkhd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtxcymhuhu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtpxlwedoe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtxilqqnld.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtzooblggu.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtceechsnp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtcugsayef.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtskdihdfl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtqsmvfeqf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnagtcdyg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtidvwidwj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtthghvibp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtnrcebwbz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtisblmggs.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtcfazeirw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gthyhpemjr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtjuegpixv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtllsqabjw.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtwqpprqjn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtcugxkaco.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpgwiujh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtlkwngoty.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtxijrbazd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtwbvplazh.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtvmnwktbi.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtqfwizifz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtxkpomcnj.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtvcnnvtaz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtxtvtlahm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtyiszkzno.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtjhivphql.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtsuskgmfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtvjrwnrvm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtwijdkofx.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtkqilmmin.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gthjamnolz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtesmbkopn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtcscvlltg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtcdwlaxfg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtspnwxynb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtyangqrpk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtjymdgjok.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtkopppbvh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiysbhfgb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gtpdytclna.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmlkbucnc.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gttjbwbvcn.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtwccbulio.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtosdekzuh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtiroctabv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtfjftusij.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtumewfzin.html

);
来源：http://dali.cdnleiting.top/Article/details/gtggbguzpq.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtlqbsbrmo.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtebcehkxd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtjhlqvpyl.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtlnmsxsfx.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtranxfnyq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtnhwwybar.html

);
来源：http://dali.meibo888.top/Article/details/gtiapjnqju.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtlrplhymp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtlkglqbtf.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gterrobnzh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gteaypxmju.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gttovdoisl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtzilokrzn.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtviawbcqx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtfxytdqqs.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gthzkuaatp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtmxiyqatk.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtxcuktxlm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtbochhvlc.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtmowbwlfh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhidnttn.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gthavsluio.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtwdsdaxui.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtbawtxyer.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtswpvoefm.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtjhacvhsc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtrbjlsvpp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtlynjjqsx.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtaotbagkl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtuefoigpd.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtnqxtxqkj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnjqivqm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtlbvjwsrg.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gttztacbbt.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsznnfnfw.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtqwphemlu.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtrzsnywha.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtgtrmumrh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtnyonxwwz.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvyomfie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtuwgwfobv.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gthvrkgurz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtnpmgejlg.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gthjxpswsx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtsitjrtiq.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtvzgbgget.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtbohgnysn.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtwjthowwg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtbzagrjsf.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtznnvwbho.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtbbthyump.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gthfuiwhoi.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtbnkkhxtk.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtqxyqomgk.html


<!-- 参考信息 -->