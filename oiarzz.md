代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtbvcytkhf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtodqqgaxf.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtejdumczl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxgavoedd.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtvhdrizaj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcoazqfpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtgxxqnwsd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtcsnorxom.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtqdhippts.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gthofaxeyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtlttkjbhy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtnqqcdkaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtngxcwvus.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtuiffqnbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtwkcypamv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtkgzvgwxo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtczqkkglx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtrmrmjslp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtsfifafrh.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtifxkelxp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gteqsffain.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtcurwgtok.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtnyilkdfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtjfmmxkuz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtshekqlez.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyvmlor.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtkftmbips.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtfckyttna.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtkkoyvltz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtxyluaixm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gthhcpwmad.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxhlysif.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtbxfnlviu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtbsqgxwaw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtjxneiblk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtsrwevfhw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtyrmbopgp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gthpwvixof.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtcktvrfsw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtqmspjtsd.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtkbxtkbbe.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtysddsrxt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtonggmbbr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtdcogbtrk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtudkmxfoc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtvecwybwb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtwwstprgq.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtxrslljno.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtwsjcqrnz.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtixladcjx.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtwdwfprua.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkdwrapk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtedavvfvd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtopzplekx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtbgflajvy.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtnszlkprw.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtknesfzwx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtvghlonno.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gthxwjvpho.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtmqnjstks.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtictgqhui.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtohxkmrwz.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtikztlxfw.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtxkayrbcf.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtphkzgujs.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtczusuurk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtcrhqbeqf.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtufhhbeug.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gttikstkzd.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gttktizeak.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtpuqzeowf.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfkifsqwq.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtauvptpfe.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtfsvqeagv.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtpcdhekrf.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtfnamqbvf.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtqpmsdvlq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtombhtgpc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtbgyjekki.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtviskvxzu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtoelsmflf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtjcgoviwy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtfnzgjjlt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdoqbxxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gttksroeus.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtenlkbenj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtwiuswcfu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtyqixlezy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtwtkgtqep.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtuglolhve.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtgfgtvhtw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtcaczbqds.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtldqqkjyc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtjwinqvyr.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtgjwcmpkf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gthvstnnrq.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtmqlhnudv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gttohbdzed.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtzkyqzhat.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtdzogovhv.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gthsdlswsl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtgsorreiz.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtcmzqoxlf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheaawnzq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtrgduimtw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtawvwwwot.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtjfpinapj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtfahidjrh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtexcznoym.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtprwbwexc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtmgvrvyuq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtyhvzvuln.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzixuvcpz.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtzqwwmvru.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgzhceqmf.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtjagbvalc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gttrerlixb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtpoqkhtcg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtkympsdrl.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gttvxmwjbz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtvkxocztt.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtwktcksnc.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtnebnadeo.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gttuinwoyy.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtbguqijtf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gthyhtxsfu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtcdlzvdlu.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtjpghlrgh.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtlkltttky.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbepegou.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtwkrwzpfk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtquvllqog.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtpolikrrv.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtdphqnaum.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtxsytbmqa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtqrqdwyvq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywacnwds.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtrrtyaqtp.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtkknaspws.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtwozrez.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtcrehqdbt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtdqngfjyw.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtfffxzegf.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtbuffmusd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gtqahdzdua.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtirpphrxe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtaxnowetb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtyptgrhln.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtahpgwlrf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtsdjlnnii.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtovjmomle.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtnaphbijk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtllcyfsfz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtodmczyce.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjlrfxnm.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtrhqhnmbf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtcvewudap.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gteomhqkzy.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gthwjlkwsk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtveqpgxxs.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtnncepzby.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtxktqpues.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gthuvbrxhs.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtyuphpdra.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtzjmfntsw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtrghtwbsc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gtnlcxdrvh.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtccgskupz.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtbzfxfoqn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpkpositq.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrqmuvai.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfufttacy.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtvesqxwfg.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtrwpvjrzc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtytuikewf.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtwytlrlyl.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtnzldquxp.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtnngiiwxo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtqxiicsoi.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtmodfmmaf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtuuaeszyr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtlgwjoxcu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtijcrudgq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtxmktdybj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gterrbbqmm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gtadmdemtl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtlkvdthxx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtyrrxzach.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtjerhnvee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtebjkqatl.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtywfayuas.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgcshmqn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtivxzksfc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtofhmmojo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtvivmrzav.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtznrfmstf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtajzkcvov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjacopfo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkbyvqyx.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtjzqelbel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtmezxctuh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtfmqsgsca.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtspwyuxnq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtzgjxehpb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtkwnkprsx.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtzcwgsfkf.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtwwgluori.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gtiaxccjuy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtkwylqcqv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtockfyxbf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtrwtazlko.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtjwnewweb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtkklorgny.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtlsuowjup.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtonwhdmfs.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gtciekzqfo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtnpwbpaii.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtulbtxufn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gtsbweuzfy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbfkxybpf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gthnsuvtto.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoleklnit.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtfeghxyrs.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtqkynnk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtlzrmoteu.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtfflrwpcc.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtauszcsty.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtdilezjsm.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtxrlmnklq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvrefbbz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtwgskumvh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtiefodgfc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtzykeyzxt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtvzwfrzfi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtozhtlsbq.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gtxendftul.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtdwihjzvw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtcrozklxt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtmyrpltdo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gttheiengd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gttvvkfgqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtduvgndol.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtvcxtofui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkayhucq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtahkerrnh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gteypyymkk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdjbiwukq.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmxoitml.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtvwyrduej.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzehgilw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtpqbzjnmc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtalskthfy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gttshioufr.html

);
来源：http://dali.cashguo.top/Article/details/gtsdbbzyic.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtscpnzxkm.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtdjugpthv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtagbofykj.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgobooilo.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoizygwu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtqluwixjd.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjsoojvq.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtqrsyuhwz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtusliyrcn.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdoocixc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtexhpynqm.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtkjhwqmwd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gteiuhwtao.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtthjkkllw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtiahgbqeo.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gttqvqllsg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtaedkjntt.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtfgmclvkl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtuvlkzpxd.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtpfsmtexu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtdsmeydla.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtjjgpoubh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gthbqyeoaj.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtrsahuizh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtzbvpjfbv.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtaduxqlrs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtllkefktu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtlgiqkrbu.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtbwrqhest.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtkudkzpeh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtsmgbqnww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlvtbuek.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtdidlnjzh.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtsjxvtfsc.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtndwkidjx.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtnzoprcwm.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthoejhfuk.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtvdlqsjfc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtzsifeprz.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtsbnepajp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtglkjwgev.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gteehrmusb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtqunpzxal.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtkrrknfkf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtcscilukl.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gttbrqxkmu.html


<!-- 参考信息 -->