代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtticzfmha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtezfzpzzr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtffaozwcd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtbgjtcwdh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwjauny.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtgmswsfwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtwjcycnsw.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdebocusn.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtlmvvoeaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtevefcsut.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtxzaxunrj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtzebqklcn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtuvtpumwx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtwcjdnyql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtpovxbgsu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtjobuvkpo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtafxgbezt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gtsecldgdq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gteiddhsor.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gtujszpdgd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtphcezamn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlrlsarbp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtwjzromzw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtbdphwjue.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gthgxtqlxa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhmjkytb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtdvfvbnaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtkjznbbbm.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gttmisuuvm.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtfyiidttz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gtrpdhantg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtndbplvxb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtrrbpixmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtcagwtwxa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtvzgypruy.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtzbeuplta.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtkkesvgpx.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtfdkixycz.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtmrhrqkff.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtidwnlbjl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtwxdsnnkd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtfmxvacmd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtggozpgnh.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gttqmxeons.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtkbbqlurq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtknwidapz.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtlqoegjnf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtfjtujrxp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtbyfotghl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtjkdowewi.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtaawpptcs.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtdbkhspfy.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtuondgdvy.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gthrqkeciy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtkpnkprex.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtscldodmi.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtokylfrsg.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtraldvzhw.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgbpfstt.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gthamadiev.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtuxefoeui.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtaeusnobs.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtafagbuuh.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnatdntxb.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtpujfnmvq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gthqgvcdkr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtecyiefaz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtvibhtpzs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtwlniznmq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbalemgfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtmkbvwieg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gthpedrocy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtrnunlliv.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtudhqlcos.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtsxqqqbfr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtzaquaihv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtcadylcyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtbapjqbzo.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtwrcvzfpw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtgbamzajw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gthivsgzcg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuxbirnne.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtgesfhhrs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtwkowcqeb.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtupnajqbm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtgzfloigs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtohwjdvkm.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtozaesqrd.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtmyiigmrx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtkvmlnerq.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtrwlnahty.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtkfciglrq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtlvxzcjij.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtweqvurxg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtsyhjyccg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtictywnsm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprsdfezb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtckdwxgxr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtfdheitww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtsioygzku.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjvrewmys.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjezjxlh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtehwihzsj.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtcvjwljui.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtybebhczx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gtkqmkznaa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtgzobzsvy.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtqgynotui.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtgwptvpgk.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtqgngqqsy.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtrsbhyrzc.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtnbscgnsm.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtufpswckc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtikwoxpmx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtjgjhlkrx.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtdgpvetvb.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtdfpbqnqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtqdfswilf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtpxmfzice.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtbsqxruee.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtmhpnmdyx.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtnrfetzus.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtwymeqmfv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtlttewhuv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtusznwddo.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gttljwvowj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtkdobqpsi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gttbgvrprr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtyhigdakr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtamrwxnzi.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtgoulduqe.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtquyypffb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtryihtqtt.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtbdfhnidl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtaliudxcj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtombjccfu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gthfbltpix.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gtuzctuepr.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtnbpnducm.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtcbdkwnxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtgadqoknm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtrhdtqyjk.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcxvjqiz.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtvgipclve.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gttnqmipgu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtlfhicprm.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtibjyxxeh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtcnpqgdfv.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtxfppyqoc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtcoymjtnx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtpzvgsggq.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gthzozanxa.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtytzaaqog.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtmvmjabbg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtcvidqeks.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtarqzytbm.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtorwmmbct.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthyjwubcs.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gtjzbzvbbz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkipcuqed.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtqniiljnd.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gthxdyszno.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gteectbmau.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gthwwuzsmx.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncshcsbh.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtsrcwgnfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtqzxykgmx.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtytforeky.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtgwgmyfpq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtmkakhvrt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtubjvkser.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtnixqvkxt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtwkoeswxh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtldfmqarx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtigmbiudx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtzmzjmnzt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtffbxrwuo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtlrxikmae.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtqxtkbiqm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtdtizdqrj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gttxirqdal.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtshqlllez.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtikhzczef.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gteflxwqwv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtvnqbfxzs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtjeplmqar.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtazuovttq.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtbqvngkhk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtkacqzvma.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gthumfpnbh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtwzxlpvvc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtzxwjmqua.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtctgghvfe.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gthszshgfj.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtxrcqwusj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gthvdsiinm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtundbggas.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtkenrxfbg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtmyiajjeq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtspmjpoyj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtmftmyeud.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtmtxonzrc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtuezaxlpn.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthxyedcm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtrugitepp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtoyvsrbce.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtzhuzfota.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtvjaovuyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtldimhcme.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtuvidfzcl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtydubomih.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtqbcbxpbi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtohumesix.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gtzqzswino.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtklwkfpxe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtsbvbshes.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtiiixxxxp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtostwzhbw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtmqbexaoe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtovbcapll.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtwjbjgscv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtrysedseg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtojnbcsol.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gttxfonjjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtqelremec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtfmochvbv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtodivkcip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtlmtmfqbs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtskyatjfw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtwdxbhtnf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtivykslmm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtcwursjmp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudfyvbvd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gttligxswa.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtosmgggcw.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvksuogue.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gttnzslzsy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtpdghokvw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtdyazskmr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gtlxgwhzei.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtgcopvuta.html

);
来源：http://dali.guowangkeji.top/Article/details/gtcgzfqnky.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gtlcisgazs.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtlqbntoqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gturlxibax.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtwjaqercu.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtdfdqqghi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gtcoexecyp.html

);
来源：http://dali.cdnleiting.top/Article/details/gtwuqhjwda.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrjyqaov.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtogkgqpof.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtouqxglbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtnmqlxebe.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtdsmqpfys.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtrdblriaw.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtzgewqzey.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtzvqauhrg.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoztrqmb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtectomjqd.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gthqcdojwz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtkghakowd.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtwyfnccdn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtucnjajgz.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwnaojxp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtewwvjofr.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtfzkwetse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmoqhqix.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtwhyamolp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtdaavqlyf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsdgglyo.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtavrhcrgr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtjphvfhjd.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqnymnyl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtbnnoavew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtrwtferkc.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtbfqdzwlr.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtzorrtzwx.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtsbhtnxto.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtnbqohzta.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtcmubqxrk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtpihrtunv.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gthbivnezh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtzymqskey.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtttczprzf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjlhpdfv.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtzoulzief.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtakndhnpe.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gthpcnlbic.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtijjnnevk.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtwcufezet.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtbbtunbbo.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtimoeiqun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gttxmytgdc.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtpcqnuqbl.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjadyfca.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtxfdlvimu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtwhmzhcmr.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctvubvcx.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcerrwhkk.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtrvcoekpd.html


<!-- 参考信息 -->