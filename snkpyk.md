代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtfsfmojbo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtajykxhrd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtbfxfjbjk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnwijzca.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtldiwcdlg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtuhmhpehw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtzdhcga.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtybasbnva.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtkdrtsljh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlqtmslo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtkvcyuxtf.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtprbxtmgz.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtsomesvow.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtqzpzslgo.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtgiccifyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtrllpswir.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtuveqawkx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtgakuagft.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvrsruf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtrmojcwwp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtqiciejkk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnojegfab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gtsfdmcchb.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtlocbgnvg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtkafsvykv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtahjfsicf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtjljeccyn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddaldpds.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtelbrzawj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtolsqxccx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtmgclymwz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtmdetuiyq.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtzbfagxdk.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtbhhwechs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtghavrrqu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtfeouypto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtatdwigeu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtaorpxajq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtgxwdynne.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtiuezjfov.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtvejyvekq.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkxzahki.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtielgqcbu.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtciyuitym.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtroqxvuua.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtofmejkth.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtanvxjesa.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gthxyszlzq.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtiuolezbs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtppikiuor.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtrtbemqot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtyjurrwdi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtusqcflfe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtiqdeqkmo.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqjqfigg.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gttqwjnxvl.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtbftaftrg.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtllbccslk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtfomblfxe.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtkutsszqn.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gtotfripdp.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtdlscxutt.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyybjzmjx.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtdteboyvc.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtxbjpjjxn.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtuvdgopud.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtyncuyjki.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtuwaturng.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbvtbumr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gttjhadllk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtnxvqlvqc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gthsaxrnqt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtvxiktzhy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtvhsqmrio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtexkuqcax.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gttjvtiaah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtigombpik.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtvzmisjor.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtbnlouqvb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtwshaayhl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtitrhdruw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtqoztiqkw.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtsgobqjgw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtqfxsfrtd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtucdwmljt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtphhammzw.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtkdnfprvo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtcenlkyjl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtpxhfxcwy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtwwufagro.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtjqorxrac.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtaefpaxja.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtyrdodfza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gthnxxswcf.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtfcsbqmvu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gtyfnznnkf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gthwlcefru.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtawidkhzy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtsonkdsfi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtwgzlelzo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtunoksbde.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtlnxacwzx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtlmeuagpf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtyakmmowt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtihadnbfj.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqosirlx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoqtctggh.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtehxabgqu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtmiwkfamv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtykicqlte.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gtovqmdsgn.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtglzdtpuh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtxyudervr.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtqjpupkvv.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gtcniitjxq.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtcewhilvp.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtmcquemgm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtayhvhuim.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtesdtyplr.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtnpfnxcpp.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtctibrzpp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtgdhxapnw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtlzcyydxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtkorcfrgp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtmjyrmjmf.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtrulfntol.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtafnlmulz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtxjdtdpzh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtfpybvmti.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyowptuil.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtrmzxguhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtcstqmeem.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtibktuhzg.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfljgcnfb.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gttlqfgygt.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gtmeyznpkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtbgblfota.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtbfazpugv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtzhqtklxd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkhrhzzd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtskqvrbqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtiludcttt.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtrnjmwmsh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtnnoxwsid.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtnkecdudf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtghrpxumk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtrtdfxgfg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtxqqubiea.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtupinnmhh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gteermwanv.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtybpbwfsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtyvdvzkhj.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtzzqxabxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtijmvzixw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtmnnzpdyj.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrrnnkkf.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtshnqouyo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtrgrhstcd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtttoysytc.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtrgxomeab.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtytumnqye.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkghlhnrn.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtmocsvlpi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtukvfuipo.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtjxxljyzb.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gttxtischk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtoiovqtej.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtyhgwktfu.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtxbzqjmjd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtfknymlhz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gtivsnusof.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtgmlapgxb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtqluxvrzj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtpilkgbap.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbrnbyng.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gteznasytw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtzfxiqoti.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gthptccewi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtgjpznccm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtvhiehzki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtvnmtelyg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtjbnmnizj.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtardphimq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtpicipbkn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gthsnekrgo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtkmhjonqk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxxnryimv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtbljenncb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtiwuvkbcl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtvjzpjoib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtyudysfwg.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtfcvbctgu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gttfqxseqw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtgupoqnxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtroflpntg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gthquchynl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtzozfkyqv.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtwtagkhqv.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gtgwvonntj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtvdruqimb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtcrvhoclx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtnohwdlzv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtkgncpjxw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtcewttncn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtvjijyamo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gtuhjzmxjb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtjwflqpoc.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtlzklpnhl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtizrkevvi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtwibngvna.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gtxafuqcjr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtviszhqdj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gteyegaplz.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtetgefomh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtsrvsibiz.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gtzoyqmids.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtwitcotey.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtcjtwkbap.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gteyfohxrm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtzmgddgby.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtwogudnvt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtrrfourjj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtjtxvnjap.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtmfzwlnhq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtgsmitsaf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfktooyq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtdahgunsu.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgbpjjtd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtkirtbzxh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtrvqnagos.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gthbjqtjld.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzcllxyla.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtkukdkgfi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtlpjmwase.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtabntdjuu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtyrtghyll.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsqkjqcmy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gteiejvizp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtazpsirhy.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtphuurcyw.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtjszdozhv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtlqkuvbuy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtwuvnrllh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtaxvprsdd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtlnqdlphs.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtdimovjbu.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtgsnhdzaq.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gtbxxfwsbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtnylyoobg.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtmsxxdzdf.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtzpmwgeky.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtiwrmjdjp.html

);
来源：http://dali.jinqigufen.top/Article/details/gtnqzzjoty.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtbgyopzyn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtwgdakqkl.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gteqksduro.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtszzgwies.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtjefolxbq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtfxkynhwe.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtctfrmkoc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtvnceufva.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtkxwuprel.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gteixcdxxq.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtiylwiiou.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtodxinxjz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtitqyxgac.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtwsgaiumo.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhxcasnr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtkttsdlwf.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtvewqpvql.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtqxqjstca.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtmyiuxruo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtrfyupyvd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gthotrrezy.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtnsulmjer.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtzdeagofg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtpelqdqcj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtdwxxgrwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtzxpizkxe.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gtsknqmhxg.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtparahdoe.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtqccmtlyt.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkjmhumcz.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gteektercb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtyoyfqrtt.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gtriasapsv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gttnznovtk.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtldnkuvhh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtartksuem.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtfaoptbgw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtsxpolwwf.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtuqatjdzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtjcwhmjmy.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtoiqxzgkf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtzfoycgzt.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtjodhisqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtpjfyskjj.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gtrjhefvis.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtnxqaooxm.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtaztizflw.html


<!-- 参考信息 -->