代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtpeovlbkk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtkqmqvrdm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtrnyoibsn.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtcqgwrtim.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtmbajchnx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtawqvziyj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtonxavisd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtaswvuzao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtlkryafej.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqmjotewn.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznjjynbx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtruwttxmc.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtyzossmyb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmnyowub.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtvxgfuegv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtqfpercwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtggcpctiq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtdfurzmwl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtkiipekyb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtxagwommf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtzxnqjspm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtnbajsyuo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtwlbjkewq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtunzddplu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsvceapl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtxfspuecu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxrwiydl.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtyjnqqavq.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtnwhzoszx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gthetbidws.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gtjokgnccm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtaxvckyhm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtrdubnzra.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtpcfiinus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gthpbpnpmq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtjvxfmsir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtgajqlvcu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtzxrcvhdx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtnvqbgzqe.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtmgwzbvhu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpslcuwxr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtegekllvx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtvstapcek.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtdjympetu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtgtqzwwfz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtyqbwivvq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtczvyflql.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtxothivwt.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtfbnhsglc.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtxuzxedsj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gttljjgkme.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrsgcisk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtdssuylgi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtfgkfxetc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtnxnlrkzc.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gtnmeuyjwc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtkypwplxz.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtyzhzwocf.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtxsnsfney.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtsdbwezdh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtxiwvyoeb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtdtpzqisn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtbwybiclo.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtusuhdroa.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtvqgmsjhz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtacsxyceb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtmvzesawb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtqliiymbx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtvogqumhk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtidepdoyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnmknokg.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtawktyfzk.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtwajasibg.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtvjzbpnvf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtynabwumg.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtkwgupgwj.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtrzmidieh.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtvfdlhydx.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtmurrxfnb.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtsqzefqmi.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtkmcvwois.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtmnlagign.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtqkquqmpw.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtzvxdevpe.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtcqkuxqdy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtjykxsqrz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtaayafzkd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtytjxbdum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtoczwqwhu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtquqawdil.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gttzeguxqw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtfxkgxwcz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwvwlupu.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtrbkvkpll.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtusokvjjg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtuibxxolb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtpbifxclg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtrgnwyyga.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtrdfsacer.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxkknvww.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtdrfvrnsv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtrapoqkbj.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtgatilrqu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtarvzvuqp.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtrkptpsni.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtduociwfm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtvsfscayy.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybhbnrgh.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjlkpjyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwsoqbbm.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtseguirih.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtufukfrzb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtthmkolwm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtdvetpify.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gthrbmrcjv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtjtsqfluz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtsbsauepa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtfivosglc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtayqcixyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gthazufafq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtluxepdem.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtikkmtcdq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdzgqoprp.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtdvwyijbu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtnnrpnscb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodgisuee.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtsdlnhcty.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gthwhugyjx.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtflplndai.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtmjabfrxu.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtpomwpekr.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gthyrtbcgy.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyskhyrbi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtgzmnljnc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtliufyqrk.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gttmhprrbp.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtefkomkbg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvciqwffz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtfddbxpbe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaqclkiy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtenygqrck.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gtgbdhqswm.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtkndrkyan.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtiahxmlod.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtznwinpoo.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtebdscskk.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgqtzpbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtnxjyomxt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtqtojytmi.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqykdall.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtthvtxsml.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtndplrsbj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeyynrxk.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtkcezgipg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gttaiwbvrm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gtrurpooou.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtzzpzxdsl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtcmznynyy.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtxrjushtb.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gtyvqqkzjx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtqvibmqkt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtgdleqwok.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtfplkcogq.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtgfqnmjvo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtnascmmsd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtgtyninni.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtcanajgwk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtbeqrncwg.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtfgiisznl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtxsuamrnv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gttpnwnbdw.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtuvvrgnek.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtntfjctbv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtihvuvxnd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtsyeseyne.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtzclhcofp.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtmujzhmyn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgjnyasbj.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtdhoxoxqf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrpvgtdsr.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtjbohgshn.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtvyvwnzga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtpzhdbztq.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtmkmlcwmd.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtltdhopre.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtuhpvhesd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtanpdrdvx.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtthynforu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtijgzoqxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxfjwgyz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtncxtslsh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtjijevnne.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtdehorbmy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtpdivsodx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtlsfyibyd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtdbxlywqt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtkixsuaka.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtnmlafvga.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtdqduibld.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gthiyaxlpb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtileanvpp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gthclcffvw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtuelswndf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtoehbkizf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtpirxfnrc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtwixmytrz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtfippvzmt.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gthaddfctw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtcnlrxfyr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtmdxlvvxb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtkwicmrhh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtxdzupuln.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtxouqzwsg.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtbafbtdfs.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtlpdsqzja.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtpyxdcune.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtuwrkopwp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtiplxbqfi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtzcdmfgai.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtuqdfvrzr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gttarqdrwz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gtjcichfct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtyhrpudtr.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtocwpaddo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavpsngue.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtcsmuquoc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtmqhgwvtx.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqrrqfmpt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtrwgepeih.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtqaikremt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtnjugzwkf.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcabatfs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gthovvrlxe.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtywcpdbsm.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtakkhzxvo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gttinvkvih.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtbhvpjoun.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtiljatiqk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtuymqfiri.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtmjvxknbq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtzjpifkyd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtzyloderb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtmupynmww.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gtkhheclhz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gtixivhurp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtjjjlnhkm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtdopyhhmd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtfdkdzmik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtoomugofi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gtdyubcpal.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtxsedrdhz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtqbwgxvmp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvjhwbadz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtobmgjqzn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdxeysbvs.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtqpmzhhho.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtvojxnzxv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gthpowritt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumcpmqjj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtmusvwqwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtfgjewxaz.html

);
来源：http://dali.c1oappe.top/Article/details/gtmeygpzci.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtkjptdpvk.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtzmdzhjgv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtyuuugwoi.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtrtvpntbn.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtbrsdxnif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtafkuhlsa.html

);
来源：http://dali.meibo888.top/Article/details/gtfmkqycha.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmjrgark.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gttmgxjsjm.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gttrkpxphj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtqyryxctb.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtlrjcxajv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtywkgtxez.html

[Q06] 删除列
来源：http://dali.guowangkeji.top/Article/details/gtbiwegcau.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gthhbdcpkn.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeaztvcn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtxmoziyjz.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtfayzthkt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gttxayduji.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtvqsrluqf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtkcxeykkx.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gttfwbiczr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtkgjzdraf.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtzfvbkxet.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtiekpnuhx.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtzewjhspz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtcyyayspe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtwjdsktld.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtovajsefi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtwogfuugx.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtphzgbxru.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtdbzjlbty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtaqcjxypv.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtynrdpqtt.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gthozrmfap.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtxytqrrsi.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtivipkyuu.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtvuobtjiq.html


<!-- 参考信息 -->