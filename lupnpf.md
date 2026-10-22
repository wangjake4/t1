代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gt2imldkdiy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2jynhphzo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnwvqogn.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2jebvewas.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2zimobtno.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2kueyddwu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gt2rqikrgam.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gt2ziyuvuco.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2ermzyyoc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2uprfdetr.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2cahxzfwt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peqhbato.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2ynhfsnlw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2iaptlklc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2wpxxfxfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2pcpzfkad.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2stzoyxqc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2qetknxwz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2agzcyjlv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2teechxmg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2tdzrbhji.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2kwmxlbfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2wvggpkfs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2jgxcfeff.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2sngiihsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2xwvrygre.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gt2lhjgwyvd.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2jemivavs.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2mqxkmoit.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2oaynevhf.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2kytgqdef.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2fqyfwnhg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gt2jluylnyj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2wtfjcwvb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2bnxpmleu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzvvlsxa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmrhnrzt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2dieioekb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2yxparfbl.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2vdhsriir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2ocuhjxtf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2qyisexle.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2bucvcfgt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2lcnypibc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2jpqqofic.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gt2gzuljjil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2fijmhumg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzjxpuuj.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2xpkbcded.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2lhcgktzx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ydjyfxfq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2llginkee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zumytbgh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfxeuclc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gt2spfcfujc.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2elfntlkm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tksnpmiu.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gt2cerbwlis.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2vdxepawo.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2dmnhvjuf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2kjoimpky.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2kobpekin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gt2phnwjcxe.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gt2sjdlmejo.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2mhrcvssf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2mbhfosws.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2oigyomzk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gt2wuvujbin.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2obapwdsa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gt2lvaomfeg.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2vcyxqbwl.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2klvftjlk.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2zinzavmm.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gt2cmtomqpp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gt2hclohfsl.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gt2suchrqfo.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opjslbao.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2xayhmdsw.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2orqdfjse.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2isubxtxz.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2asmgeprv.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhyycebh.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2wukbkvom.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2kshtlqvl.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2pdnklaja.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gt2jkerdvrp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2nrahnjjn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2mpescpwn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2zhxmobyz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2akuwcqoj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gt2jzqkqakh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2suuacuol.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gt2mcexwddf.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gt2vmbdkaww.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gt2btuulwvg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2jlkvvqwd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ypbcdrte.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2xvhencgd.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gt2bzmtyzex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2kbpnwjpz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2jdppkwua.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2kwnoxvaf.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gt2xraygyyu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyrahhvv.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gt2bbavzldy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2zmmyomqx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2zvwmlftu.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2rvxqfvjr.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2ccxwpzee.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gt2trzwjeql.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2djsowali.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gt2shgngyiu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2edwycgfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gt2hzsgkqch.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2masquepx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2qprqkiqw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2dxvzzbuw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gt2tgbfpdpf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2eiwwnsiz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2oaetbteh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fuuzzgwh.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gt2mxogrhxl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fnsvwlei.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gt2mzuoyhkl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2areqecfc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2tossfytr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2xeznnctq.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2kxswycsn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gt2ikrmhbav.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2aeahrjrk.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2yrgslbar.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gt2xgkvzkqz.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gt2hcpoqfnz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gt2knairxnk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2ypspxiam.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2xeazffti.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdlygphw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gt2lqdbpzby.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2falnwchl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gt2abhkxoni.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2xthrelkc.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvdplpor.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2apstqmvl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gt2kvlbdnao.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gt2snmppblx.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2zzgetgdp.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2hzqefsnd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gt2xliovmge.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2qcvpnvny.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2djpgpehg.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gt2wlrtgvmo.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gt2oitpzsop.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2bscezdkm.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gt2xeqmqedl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2ckecwzjk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gt2fjolfnlw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2gtnzhcoj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gt2avxdeflf.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gt2zmlpwsjx.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2aebisnum.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2rrohpssg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2qedejnru.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2cqecapvs.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2kzkazfft.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gt2xhjzemvz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqsiqcva.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2eovibfmd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2akykqafo.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gt2xynicdzh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2dwufiriz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2xmrmesxv.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2giaqqhzs.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2rgfdqyzu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2bqxguyzl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2mtupmtsw.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gt2smvsfsfw.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2aajuxgdu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rkwbtgjz.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gt2ntwgqsjc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2egbiomia.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2foqrhqzt.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gt2eszjsltk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2xwcnurnz.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2zedtigte.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2bmieeohy.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2yshihjmc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2sudmsfhl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2wvjzbqbz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gt2oondgwcj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2slbueatq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2bmzvvxal.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2bejyavvh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2yqbcusqu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gt2wulpiuvv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2irunyoxu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gt2pcptpcnz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gt2xrqbjtau.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gt2vgweaiuk.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gt2nwyzttef.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2cxouxbux.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gt2ykdawcvw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2mjjdiuxa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2kgfzkezo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gt2evwmxwds.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gt2muttdwys.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2gbnynfud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2gttusixd.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2zqorsulu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gt2eoukkrzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2wdhiiscj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2nnzoqwva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzdgvnye.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2swwiqelk.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2mbdqqwuu.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2grmfusds.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2iecunhwt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gt2lwzbuvsr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gt2mzkuxytb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2phytlkyk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2jkcbtkry.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2jevkakmq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gt2pnhowdpr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2lxwttgur.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2qwdxuywy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2vlauuoxb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gt2xznkxrcz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gt2xjlexflw.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2crmmhwwg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2rpseyevz.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gidcrxzf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2ljnehdtx.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gt2fzausqfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyguekzw.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gt2rvlkhppc.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2wbgdoabs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayfsvjkw.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkiueave.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2kxuzfegb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2svbudnte.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gt2bvfbxgvv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2vufnfkes.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gt2bypyzwiz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2wyakgsnx.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2vthemutk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgxgozls.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gt2zjyycahk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2urwwndkz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2ytuhcqcs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gt2jtnpqhdf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2ylkxftbe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gt2aterjcxg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gt2yapflort.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2elftkkje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gt2hzhbbein.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2crvgtvgy.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gt2znakcyca.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2eridojvw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2eajkkhnz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2zvygtcky.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gt2otgexbxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2ilofplyg.html

);
来源：http://dali.yueranfly.top/Article/details/gt2sgyoelfa.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gt2orfmwlyu.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2vfkipkko.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2sabwetsz.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2gcsuslvj.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2teoglsnj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gt2qufcdbud.html

);
来源：http://dali.cheryme.top/Article/details/gt2vuwbfeup.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2yutalpne.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gt2kjconrui.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gt2yvzsuxao.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2axhmvybm.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gt2mupfojqy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2vhodmsfc.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gt2zivzfaon.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gt2uexkhgko.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gt2osmpwwof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwgzfjxm.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gt2vgtljgre.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2uomxgyaw.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxfimrrj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2rcuqnywg.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gt2qjbdxrnn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gt2tujacsve.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2quzjkhmy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2fduurfim.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2pzyiozdp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2zhygvawi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gt2hocfahow.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2qlxpimfq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2iuwrfbtf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpusuyog.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2ljcwjhdk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gt2gdrtrvmm.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2zhwcindu.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gt2qfkgczku.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2jdjctddq.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2qfjocntl.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gt2yilxqbhs.html


<!-- 参考信息 -->