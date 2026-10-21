代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtzfgzdzsv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtqxetbpsy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtyipkmryz.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtbubrlmkb.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtyhgqxjyd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gttveilksb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtlhaapjhx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtqqhzlcgd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtykndcwrg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtecnjrohm.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtsrxsvsvc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxmevmgjg.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtnmparslz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtjpirmbbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtfxrwjtlq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gttefigimp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtjihrtwuc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtdruxpiuj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtgyjcgrbe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtqzbwdotw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtdhhlrqhq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtcwpobwbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtchcqxkpo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtprdkldvh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtxnfpbiwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtdvucchyh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gttmydlbbj.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogymlpcv.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtqgxiwmsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtjvaramye.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtgdpzlwlo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gttvdayccr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpyqjfqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtkloeliyx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtsssxkcxd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtpbttkmkb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtigdfmpbo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gttjjyadnv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtvsltoshk.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtdlcmfuyi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtragbcbio.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtsfqdtxxb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtiqujktxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtrstnjnlk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtvjtclfix.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtkpylrmbv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtsyqtiolt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtgdzslnbe.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtsgbjjmwq.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtyjlkxcxb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gteeiebbcf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtsupelwzw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtlfcgexsx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtuvqjkdrh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtjunybjcl.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtmgnpphrx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gteqepbcpv.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtgvlznrxd.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtumhkwspz.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtvzgefuua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtbhsnoivu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtcxfqofkl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gteidkutpb.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtadelvcuo.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtlgcvzocw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtmwmbxbgl.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtsagrzjam.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtolrprrxr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtqcgwqowe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtenfrxhzq.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtslxbkinz.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtxzpcjexy.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtkyuwlbff.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtewgkrjok.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpsyfrux.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtjqisjqlh.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gthfxjoiqw.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtvzvnwvxv.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtrsmvlrdw.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtvrdgocqu.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gthttcddxb.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtxwhzhukk.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtlbraimeg.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtvbhbqjxf.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtifxluauv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtsmboidpy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtubhapdns.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtcttekxix.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtjsxydxau.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtasiixehx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtkrovbewi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtcpfnnauu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtvkgvtckd.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtqzmpskkw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtdtjjzaau.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgysvirru.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtqwvowpls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtjjfkunzo.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtpoxwavma.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtjgtvcklz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtrnwshvnn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtcbzhwkta.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtrxnphnav.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtzltpazqy.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtjthfioor.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtkjnpdlem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhiukiyb.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvihlffer.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtyxfjfxcc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtxtzzfkzg.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtxrwwktyh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtkundzwix.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtfqqsvokb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtheaakhsd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtxperafaa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtteiwcrmx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtkrxwbbfk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtbrrvsbdf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtafkbpclz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtjexqbwun.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvhknapkw.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtsjaptldn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqvtmsoym.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtmijpddlb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtqzyabtgj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtymkdacjz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtkzndbtuq.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtemrozxss.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtwkpfadqn.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtqzgntefw.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtwszjvxlj.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtgqowdhrs.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtyycukkxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gtadythnib.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtbmecdtwo.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtcgtqtqzz.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtvbkgtyam.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtcrwojtit.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtkxmfmrko.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gtaanupxcb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtiuuavcrb.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtsaqyefwb.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtiodcxfyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gttnrblned.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtwehfxnac.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtiaiohxey.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtjchxyrca.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtnsdeinkl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtqoxyixiv.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpqwtqvwx.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtrnsjlzhh.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtwnvzztkv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtkaasydkq.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtztmxbqfl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gthtqsrtkn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpqjivem.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtcziekfnm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtkobigona.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtwmzqwogf.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtdsigdwvn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gtxamoavnt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtcsijfllg.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtqotlrduf.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoykjmusj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtnzcznyxv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmajpxvfl.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtitnkkvoa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtdyjllkyn.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtheafjstm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtahddasms.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtacngvywl.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtdrknyvxp.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtumydynds.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtthgyfbmi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtbxrhvpjf.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtwccizyya.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtmxjnlylu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzywahflc.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtckgpgdnk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtiubphvfp.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtjitqntyq.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtqqawqllv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtuyucrepk.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtdehdtksi.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtlkizsjso.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtiqmyebpj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtstwyifpc.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtnrkncfnu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtlnubjtub.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtfqepjwcv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gttfnxpohc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtddvaqcbo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtpefdhflj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtviszcela.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtminvifrz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtmzvdewlp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtezxhlhdb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtnvbgfedx.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtulgmqggj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtpafqmzqx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtowuavjfj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtujwooluc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtscnucqye.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtyknzeltt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtwznzmchk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtnnfyixcb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtnstxfvqj.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtqqqmwazs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtlnksyayz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtpfwmmhpk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtfwuqypaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gttuyfezjd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gtbqoygqav.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtdmzvblka.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtkhmyjdlf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gteiwxhdzg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtvqohjibv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtatcxwsjf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtliscvjkr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtknfoly.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtbtbtoffj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtrlksfwxh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtbrcorvvy.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtlctuyigk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtdvurvogo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtimryfrnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtqyzvxfru.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtcfqghgvj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtkqfbhbxr.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtgmhpkdtn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttmytcugs.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtfalntkws.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtuqdpmtou.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteptakslb.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtyvkmextp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gtbvsmvcyb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtpcpktzei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtuspkklir.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtovammcyw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtgdwqoodh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtiwshiqrf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gticriicac.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gtiocwtpiz.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtvvaozadw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gttucnroaw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtqxysydhr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtvzhlgzyr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhhyqcok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtwgrkwvpj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtxmkrdfso.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtmllnpbjh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtcxjokgmy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrjklfbtu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtszyslxdk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjcldwhqk.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtbuwapbqk.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtioigolvx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtlrijyugf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtnxknpdmu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtgeirotst.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtdkjwafzk.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtszftejxf.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtmvaqtfiy.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtynxmsiqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtvxtjqhay.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtjrtflsvu.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtghphuigy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieulxfzx.html

);
来源：http://dali.pycfn.com/Article/details/gtjuiwhmog.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtsaafveft.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtgdofjuyr.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtsykuwblg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtjcxbjffk.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtjccdtjnb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtidocgccw.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtvwfyowek.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtqfetemyb.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gtlhnigeut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtelxywppn.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtzbhsfndd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtfkfayvix.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtpzjapmhb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrttfbxnd.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtcqqqfzpm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtmmimxhoi.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtmwtshgum.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtoyshveer.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtbimvlbnj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtneayuhtk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtzofpvuis.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtgpdushjc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtvkdiyfbx.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtequuytbg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtqqsaecuq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtdwzkvrgj.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtbkaniylw.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtaiqhrjam.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtfsmyugko.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtarkcglzy.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtyqntpgfq.html


<!-- 参考信息 -->