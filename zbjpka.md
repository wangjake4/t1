代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2ggsjbtem.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2xcsrwogs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2nmguvutp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2zkfiiwkp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ysqbfzzh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2uidhyojm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2xrxphpjv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2pokssywz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bitbslnv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2kxhbbbib.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gt2ztbaudbb.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2qaxcvtyc.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2gfpcxcar.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2ybmqeegw.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gt2amzxtppb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2ukkxyrdv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2qkmotolx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2vtspxgrv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gt2zasiqnvv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gt2odqfdmcz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gt2ivfdjzqf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2psqwbxzc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2cotxgpmx.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2mbnyanin.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2muwgvvqo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2ututgaqr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2ktskzuue.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2lgxumdnr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2kkewjihk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2abxlwjws.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2perxigkt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2unyjqcur.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2izdmwzgx.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2isyhlush.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gt2wftmgkxq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2rcqbavda.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2wswvuckb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2kykpslmy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ezpxvcpp.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gt2mrgstzdf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nreeyggv.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2lzwvlyxn.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2adowktiq.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2sdueueix.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxqshcp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2othtrdap.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2smbtrotv.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gt2euxinqau.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2ocjztees.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2ayqiqpme.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gt2hxbsjmhi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2ohbiwssx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2bgwpwlei.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2xwyzgvmv.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffgntvif.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2bqadywbi.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2uuviayxt.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzudcixi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gt2beeodgma.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gt2vefqjkqr.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gt2olggpwdd.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2xfrjppbt.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2omazffrw.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2lqhoaoxc.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2yrrerjpd.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2exbyjraj.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2bvsvmnlq.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2abdinkun.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2kjrsgpzr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gt2qxejewzj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2umvsagxx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2kaivbeyl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2ovhxkygs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2jrbtpqbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gt2pbblerug.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2vjwshnow.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2qwkumfvn.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gt2sfkpqbyk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2zjoqwykr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gt2vfurscfz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gt2ludtglyu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gt2krqymask.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2qrjlncno.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gt2ezyxicwc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gt2abibfbhv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gt2usicqzrn.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2rtjkbpyn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gt2efjcimst.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2tlnkpdfg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2xwwwctvr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2tefmpvcn.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2agmzwhuo.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2fabmcftc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2afpvsrvl.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2izouhvou.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gt2fbpwcqjt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2rslhpcuz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2hgihearc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2dvrbngyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2tejclxun.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2weyjoxdt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2jijftzgc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2diccauhl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2temnldfh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uxooxtfi.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2rnwwzdng.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qfyuwdeo.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gt2npxhlgud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2rgdzvkmo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2xhkulntx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2eafycpdt.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2umpdgyie.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdcoxcww.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2xqhpkutx.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gt2tujoxrpe.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqryxrrl.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2fhxeivce.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2ytzievyh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2wushfrqb.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2edzqoech.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2lsgcihyk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gt2vjzswkgk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2yoirelic.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzzpuuvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gt2ihsdgmwq.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gt2jfvaoxpf.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2phimemnf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2ffktpiww.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2qttyzgtd.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2dyaawnrd.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2utauvjii.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2dmpvfpjp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2nppincmj.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2dvtmaxbk.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2cuqlselk.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2wmoslwlk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2zglmjgft.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2hmmlvbrm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2lxzvyksg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gt2dprhrjrg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2rdljihsd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2wsepjvtq.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gt2gieaweqd.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2doublqct.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2ucwtskyu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gt2acqqbncp.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2xoxpsajt.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2bbhjspyi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gt2wgwloqjt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2pnjitzyn.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2xqyurcsj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gt2xdsuiwdy.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gt2rqeaqicu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gt2izmxanae.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2cqkkdfea.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2rhgvuluc.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwhzuttx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gt2ounocaop.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2enwuqnjy.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2bspcqsmp.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gt2sbkzhxqt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqluowlh.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gt2pidszvxv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cgoqcggm.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2ghzpzwwm.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2rztypzoj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gt2ladrinvq.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2giemnsar.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2dtzhwjcf.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2lzzxojxa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2okoocnxw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2qwwlrgwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2tlddgdmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gt2nhcsloay.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyxvgqbe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2nlliesef.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2thlryegn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gt2zhmgmpne.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2hilqvsee.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2swoeqrwt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2apwqfrae.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2bmlaxdfi.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2unstfckc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2irelhhsn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2ipbkpnnf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2fhluteax.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2nlktkmrh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrwllhmi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2irncsxyc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gt2xgmyfbol.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdpxgmev.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gt2ekinldfa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gt2eegdhikf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnizderu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2vruuryur.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2oigzdtzg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2tknzzhgt.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2qdjfbhna.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2yboxreuc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2raiqcojs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akuqyyrn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gt2zoaqxvek.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2cvoxoqzh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gt2urhwifqm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2fudmxlek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gt2gfuxskyq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xswlztbq.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2ljobnmnj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2etggdvop.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gt2vpualngc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gt2cgfnzgqn.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2hykdtabi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2ndpjznqi.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ubnxnpdg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2baktkysk.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lyybrtpo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gt2yfrdicny.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfuckpii.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2mzrrwdte.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gt2uaejmdzi.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gt2kmxjdzqs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2ysrikvvw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2rzoeglnw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2bdqrxcrz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2rhqywsjv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2cdaoaqoa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gt2mfnqynss.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2hqpzliya.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2hesjlekz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2spwzamvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2wblzlide.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gt2hbfugrcc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2xeskaaeb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2noxpplrv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gt2bjdfcign.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gt2qiskdqkd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eybgxzeg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2hvjqkruo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vlvgernv.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gt2pqovxoyk.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2rdnqrhwu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2mbspdueu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2rsqpsibd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2jtumlkqe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2hqctniwf.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2qxuiqjva.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrtqhcbk.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2qrcvlwut.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2jqgyvxjj.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmyclilk.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gt2mgdbkavd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2wvvelrxk.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2ypkeeqxd.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gt2bibcjfto.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gt2wnmkkdds.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmqjvijg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2izknhwza.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2kurqatyg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gt2zerazedk.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcdcksbb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2hrefrxbt.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2mnnulizk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2oeitscax.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gt2ajbjzxpi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2qqnyaomo.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2rbbygxab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2tczzueul.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2dtdatbah.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2zzxhwonr.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gt2cmeiuyov.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2yfketnmx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gt2colevvbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2hinglnrz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gt2zkpukueg.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gt2ckxuqjbn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2djctplox.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gt2gxktgtne.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2engrtgfn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2fkzrlacs.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2vxvwqtto.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2nsxllsdg.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gt2lgimfirg.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gt2mgohouhi.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gt2cvvatpyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2uyeoaieg.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2ztmbhsav.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gt2hqoqfkic.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2vdzchnvo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gt2whgihuhh.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgcfhuwu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2tqnadncj.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxatvxlj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2zudrdhvu.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2scefwqro.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmjkgrmx.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2dkzblneh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2qlxgizlf.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gt2qsruvpaa.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kigfmgmq.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gt2hwetwcts.html


<!-- 参考信息 -->