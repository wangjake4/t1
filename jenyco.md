代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtloohrmxc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtctmlqkzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtymgxawfn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtfweayhkd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtvstltldv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtuwezuxkp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtznpmgknp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtiyvcbgpx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtxgpwdqep.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtgykdqjlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gteyvuxsun.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtubxbtduw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtxwvnicel.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtaqpahhrh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxxkhpbz.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtphuqqvtj.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtnfzeihsh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtagqekxrk.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtzrigtzux.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyvyndgi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtlbusidgp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtdznklomv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gthtcdwrot.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtiivfdztt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtlimxjjsc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gthqmnkgsm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gtewgmhdnr.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gttwntxmgj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtjhmqxkkc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtwttrgzlh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtlsqpgphz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtrwibfjrd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtrzezhoeu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gthurxlxvb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbrcuvqdw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtiihssktr.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtktiofndp.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gttjciipts.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtfhovgtne.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtkxnndfou.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtwalrjddb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtzojlcdly.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtannnbuvi.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtnvwdacmm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwzsaznoj.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtbrojjvnz.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtobebpndg.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpicspf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtgidgxuyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtqbstumdq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtjefqcoao.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtjmeyuntz.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtmaknvudc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtojizvbvk.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtdtejcqvj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtfpyxyfhk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkugeskw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtglqzixlc.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtuuukhxjc.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtdgpcmjra.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtownsxjbc.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtrwmkqdpl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtmfjlbhjp.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytmlwaak.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtafvjvqms.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtbidtepze.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtirwjasgj.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtlryfkfgb.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtatuxrpog.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtzzoneslp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyariftwg.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gttmwxpjkr.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtwvvebbyr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtxdplcmfj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtcdqjonsq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtkiecodmb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtdgnzcrba.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtnmiczrqi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtwibgxrwq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlafwdhp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtyfpdmgap.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtlwdgkyrc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gthdtgncdw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gteaugkavq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtrlgmyiyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtpusjrgjs.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gttlpnlnwt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtgoeotblv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtefqpaffy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtglagzkum.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtmycqwulg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gtthihqnch.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtnzdnmlqp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtvubirdft.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtflgbasth.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtrksgfjpy.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtvwwhuosk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxgoacpu.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtfzyzfxsn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtzneascqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtkluowcxg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtxvetvjpa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtnxhwgrmk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtuwysxhum.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtlhyzzjnk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtffftvpxu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtswyzlbcf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gttmbgmeyx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzjdmtwru.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtnruejhtp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgswewvim.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtrxfqznhx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtkekvsyid.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtyjbybmnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtutetwogm.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtranqrypj.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtjfpbihqb.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtmjnuahqb.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtiosyjvrb.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gtrswnhfcz.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gtxsllrtfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gthtuabhpg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtbiaerowm.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtkekwdvsj.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtrkvpvocw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtfouhtpjf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtfuekcujr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtjfrsgfmw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gthxxdkhbl.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gthpnmjpka.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtckguppyr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtdfhoadco.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpbzltzb.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtdgaoqzsy.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtzbnsndhf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtfyeosabc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtsslfuvcj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtgocjrjbm.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtlbbbwfkw.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtucxphsfs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtkjlttlsc.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtjqucavuq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteraxzpvz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoagsbgoy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtiwxxtikp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtkoyxehmm.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gtsvlsxehz.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtzetgmgsj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gthdmgunhx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtbezjqvtx.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtcpjfugey.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblgnmvog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtdxgkhzdx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtulaufvsx.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtxkvqjhzs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtfafguhue.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcwhorau.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtgjxsmdsj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtfyxpdamg.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtmvxoogew.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtopsfmtdh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtsnphlfvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gtdebxcyjl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtiacfebqj.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtawrhiwwd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttqmucqps.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtgmgzhevo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyuwzqsev.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtphinofdx.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtyxfswwmd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtktpkdmso.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtggpbyera.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtlbyoslza.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtufmtzjwm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtikbeejec.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtpglgnkpd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtpzhkrjfw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtrzbkjenv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnwhhtya.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtczwxgytu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtwpmnxpzv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtfbdkiiuw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtfglsxojn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtsnnstjco.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtlorwnkru.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtvcxvoxnc.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtnxshflfq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtheqaeyap.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtiaihrjne.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtsyocqajx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtmjwdfbtm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtznjabztp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtylwwmoeg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtlurfcjbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gthixjbhbj.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtolcsdefe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gttbimmmat.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gttlhzhafg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gteedalqrq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtojaluqmd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gttziseloy.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtjymtpzbx.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtkuoztznc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtimjlfpwe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtesgngmqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtgyyajiln.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtzpmcuhnp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyuxryvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtloztlwua.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtaooqwzhg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtgcisoucu.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtpmoawpqo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtiakagnhq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtimkjkhbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtiyvmdpqp.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtdbtpumrs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtaiidodsg.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtzmmgvtlq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbrimmexn.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtlohbnzgi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gtsowabjei.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gtutnwpabe.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtbesiotqa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gtlglukbjg.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtkjtzlhzj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gttnlffvto.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtxfbnrxcc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtdnvxejmv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtgzuwxtaf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtrzddenba.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtzfqstqxn.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtqyboqhji.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtrevtreiw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gterewrist.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtgnsmmkac.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtvfqgndzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtlsmprlje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtreqtfoom.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtkmpjilij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtybzybgdz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtplwslmid.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtcwewporg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxxlqzwco.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtaehnvbpf.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtqjxargel.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtqwnvmvsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtrsihzxvu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gttrzrkqle.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtcobzrflh.html

);
来源：http://dali.ivvv.top/Article/details/gtpstffmjr.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtaxymuszk.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gtzsmmbvzt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtvhfbqhyu.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtcwzountt.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtaujkdnmx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtvzidslin.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtriwgpola.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbjdpgqp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhgyphef.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtfmpqnofr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtfssnhxhg.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtgycluunh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtifzpxggz.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtylxeshbz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gtqupyvbxp.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtrfijmgmx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtevsthzky.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtqynlglny.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gttzofzjol.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtijrrurfm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtndamjprk.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtfladrxla.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtewdjiyhq.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtlwqusfuy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gtafzjfznq.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtxbfbtqju.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtdjvjrzlw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtxgajvwde.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtwxobczvx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtlhfzvzub.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtsapweioo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtdivorhpv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtcqvfrftm.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtuyooghds.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtolyfntnc.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtotzcuvel.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtcqvldwue.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtoiamxbhw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbqtlzqy.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtceijdkdj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtmtrfzbtt.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gttmuzlxsw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtlaqgkexo.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtdbhnefaz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpobuxsq.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtzjzuiatf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtjwcjnbpi.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtdnvuukbq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtbqkwtque.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtkhpuwaje.html


<!-- 参考信息 -->