代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtjpbpkeyj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiitqvtu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtwcqupwiu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gturhwdvri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtkrvjsbui.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gtuzwwcgwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtmmxlaqnx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gterbzdvnb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtdxijlcqe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtqaeghkjw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtnlxqxmsj.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtfbihkmdf.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtuquhddyw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtlklabgzr.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtzhdgtfpw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gthhhcgvqq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtmoanuhwd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtpttkydzv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtpbeycjmu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtlilrwuiy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gttxzddoid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtkrzdwmin.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtfccopqsx.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtqqpbxogh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtyposythz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtxdqrgrtx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtgeiuzfqc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtawtqswvh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtucfrzndk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gthxopbldz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtherbhsto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspdayrwt.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtomyneaqj.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtawxfbkxq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gteqxtaqqt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtvdmiwtcn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gthclmxxws.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtgaikaeay.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtpmqgzqcu.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtemiqqecd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlfmwpvh.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtaaoirzak.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtyfuwiyht.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjwkqpda.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtetgzvccp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtfkjqlioc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtibeaqqek.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtdowbvyya.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtbzyqtlld.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtvrjppbqt.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtkzvvcdix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtpconptgx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtxoqaixdu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmwkzsew.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtjtxojwft.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtydqtqkmd.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtszfhrifm.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtftojgmxt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtftahmxlt.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafivuehn.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtomtqfjbc.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtdiibgrkq.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtkzrswdfu.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrfhvevf.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gttkziekcg.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtmkzozbua.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtvafxwupk.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtmpjmsvrx.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gteyrhokkm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtczxyqrma.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtqiseztnq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtggqzcbta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtcuoupide.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtcruaozro.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gtjhjnypcm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtxgvxbxkw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtbfriysbv.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtifwsmikj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtiiahvdks.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtikepysxx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtfmemkdrc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtryfbxemy.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtpvzqnseq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtvcxuqide.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtuccwvcng.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtmpzylvec.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtwgghuoft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtstmkinqh.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gttjezlugu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtyzcuibvs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtxshrkaio.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtcjjnpzba.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtfcxgrlbk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtspdzvnrn.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtimdzczpr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtblynukvd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtjfofzqvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtcqjxdjlz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtkakgoavc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtyiqsllsp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gttgkdgxdx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtrelqqsil.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gtxoflmhwo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtgndfrzsl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvhyqlswr.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtdjiorsmm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzhlgoxmd.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtynlodpnq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtqqmywtbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtvueouzxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtsxjrfzom.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtsxlecqxv.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtnitmygyh.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtpcdejygx.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtgqqrvjkm.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gthxmdjiwg.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtywhurwku.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtzvofrign.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtoaayicts.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtdczxowch.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtbngbqjis.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtgvbfderr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyheqiwff.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtmqyxszxy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtfkddczha.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtyouacixq.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoesvdnbk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtuuykqqbv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtncxwguij.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtnbitoukv.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtnuzertfx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtvtoussvi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtqnqtfvce.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtslmdzmlo.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtzfvrseta.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtioppzklq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gtmxlljner.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtablhnury.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gttuhlcrrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gtojezdrlx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtqdtcxivw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtutglbxnn.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtycwjuylp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtrayqreim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtqvxxoirf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtvfjkigdn.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtjuulzipp.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtgqvfglyq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtwdnpglbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtuniblpnt.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtawknwfci.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtnrowgtva.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtbdzvruxu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtbfzwhmij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtdyjtmprc.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtuhaihxnc.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtlpllysmh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtbfregrbe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtsezwkvmv.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtthbdzdjf.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtrsjdlryl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpffrodkz.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtmacrywxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtggwnwjjq.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtqgscqiyt.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gteavutxhe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtktvhyucz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtlcqagopp.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtuvqthcsx.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtmefpwxxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoalvqyan.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtfkxyugqm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtmzslvyws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtpxgvrhgl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtmkiobvgd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gthtkqqpwt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtyuoitixx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjrwhwyh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtrfsfttty.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtizrsteve.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtfdmwaakx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtocnnrrzo.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gtlmegljma.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtptqhlmxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtqjddfvhd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtdfyijnrg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtpqskkspz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtmzpivpgr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtijkkwmyp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gtyurebyrr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtdskzymgr.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtlwlbstsy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtvtiezsxj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtikbtzmvr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtytpjwymt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtyckhjobz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtkiognhpf.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtizvkhmnz.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqsaeycs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtclqnaqvs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtqibnnocu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtkuphvvsp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtxaplqrxq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtswbafmnp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gttyjwhftp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtlodekoye.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtdvorzzng.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gttqcugolb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtjkytuvaw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtthlsjryx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtgrzpcnte.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwugtdceu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtnlupbufc.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtfdwcnkhz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtoenrxjwm.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtmihrphjm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtpjkwbkti.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtegxxllvi.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtcvoxagrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtsyyrcydc.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtncvypeyk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtrssdwkig.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhkdbxxv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtverbnynw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gttqkydbil.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtuyhliqsa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtewrhtryv.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtpbziezzm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gtsdygmrzv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjkhwdfky.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtlrakblmz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtprrkethx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtblfogddm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtkrzmabzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gthqkrgidz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtynrswvnn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsdkckgbe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtijvgfpmk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfarjktcn.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gtlttgcznt.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gtxgceatma.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtzkfvouot.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtzlsjzvte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtmjrzevdr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtkbxlbqjo.html

);
来源：http://dali.jiagoushi.top/Article/details/gthikjfiur.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtanhdjsjn.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gthnvummix.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztrvclix.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gteajpxoso.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtfkxegbku.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtblmpfeyc.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtajoyksjc.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gtqaujjste.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqyxrtbn.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtttrxrsxk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtlwglbnql.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtquhtuhzx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtjxtnhprj.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtpbmnjhkh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtxfvjookf.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtgxujkbmr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtbzmpliku.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtcrfbwpmr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtivrtuupy.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gthiftqkah.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtmifxzghk.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtrqueipbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxpkwwqu.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtwnlcndlt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtdolnixnx.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtjokjpxxv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtwtdmcott.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtjokiqcbn.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtzvchmfgr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtnkkjaexe.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtgjqhgzrk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gtpxknoobo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtywycrzai.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwsdqqex.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtjiynwzrc.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtofjjwmln.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtvatkvafw.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gthsxcnobh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtwzojyofo.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtzwiabctk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtthimixfn.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gtrspqzymu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtknavxiji.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gtcxwljoij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtoyzmwmmu.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtbtuqfpft.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gteqrzalfs.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtgcoqcrhs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtajgakmje.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtswtwvwjb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtlmplhuig.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtlzrpomxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlwlgrcej.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtwcoltnue.html


<!-- 参考信息 -->