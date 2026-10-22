代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zywjoahp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2ywgetrnp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2ytbomkjq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2pgxkcqot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2labrugmg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2kfpwebnv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2gorwnkrh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2epzhrwpr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2tmxglylo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptpuyyam.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gt2bfceokap.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2dzxoispk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaecgzmy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbglhkll.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gt2ycvydzcp.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2zkmefmqt.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2qyzoqbsv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2didjacqn.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2eelquuia.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2vpsprafu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2xbwykrfw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onysqdeb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2fqrmcyow.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2qkqjfhji.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2jzckvrol.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2dbqpamle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2yizvdfdn.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2rwxleqqs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2pgmewduo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2gqcpafcc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2zxlbohjd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2ypshxliw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ccmtiwwf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2bzndgdcm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2hgehgzqz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmrcshzx.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnptdloy.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lefvcwfs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2rjgpdwwt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2avkxbsyj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2fuxgezou.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2egyqcgsn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2bgnyzkix.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2hantlfmh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2uyslrolo.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2lihttror.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2vjvmjecj.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2lswlvxsh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2bxqfpqok.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2qjlglzgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gt2iahpcpxh.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gt2uxpxthny.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2lhhgyicf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2gugiqsjy.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2zyxzlkps.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gt2mjgcossv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2mgnsldyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gt2dcstblao.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gt2vypfhkmc.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldpcwswb.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gt2jggdpjqc.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2bxdtckty.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gt2kdotenjq.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gt2lwimogeu.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2ahmlgtwx.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2kindsynd.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2rnsejzuf.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2erzlcimr.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2xxogazui.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2olnnijap.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2nonipumu.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2umeqnlyn.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2xtvbjjxr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2axwwlupn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2kojzctmc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2zomsphmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gt2hlyuxlia.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2ppslptif.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcwcholg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivluoyfv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptylsdhz.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gt2uoojoshy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2ppuaeczy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gt2lizllvwb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gt2cymcfufr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2glusxank.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gt2tgxtvlzl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2qezyjqsr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2wptrpogx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvovcxz.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2sfqlylyz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjndripf.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2hxfieydi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2nctbevwp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2anypslpn.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2hayhwcif.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2qhxaemfi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2ymuujarj.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2ymszjfmj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2glwpajrp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2seahkndj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gt2kfhdjqkb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2tzqnbfim.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2vzjzjuoc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2nsdlgyha.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2vddroagf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2jgfobltj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2bqtefaij.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqjwlwoa.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2jzemxkqg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2rmfjznco.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gt2aaxlogvs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gt2byqkenlg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gt2uvpnnqun.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gt2bxatblol.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2qgybayna.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2evnwrryy.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gt2amfxihem.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gt2siypbuyu.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gt2flnkzsmz.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2mnwjqmqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocsaukhz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2yhjveiha.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2bnksgzcx.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2ppypltty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gt2dgotlkua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2xrvzcinf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gt2pjajwqex.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2gngqopwe.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gt2rtgfoajs.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2hscfrdhm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2btwolgtg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gt2gylyhxvl.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2tsxfttnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2jwgxkmjz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gt2nlzabqis.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2pxtkrctb.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2selndfav.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2itvwpnnz.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gt2tjqtyhov.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gt2kjhwaoee.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dptovfdb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2pnxkbzet.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gt2zwoiolel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gt2viznjtuo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2uffymjve.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gt2lfcfcruy.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gt2ejgsanit.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2fgjuekcv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2gluejgro.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2ntuqagrx.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2yjucwsyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2nksrsuqh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gt2hwgmnxxu.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2fbdvtajr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dglfpfwd.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhymflen.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2hsxwcmms.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gt2ujawdjzv.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2dwwphfyw.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2zcfbkvxk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2icwjqvoh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gt2ldmmelsz.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gt2lhtsexcn.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phsunend.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wpuezmmw.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2maagzjtn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cdzyxylz.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gt2bozkmyco.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhqsgcql.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2fcryfmvn.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2uoauowzg.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsxqweun.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2enmfuftp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2mrnzwakf.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2flfreiev.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2bkuzqpnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gt2lbkgwqqg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2wpmqburo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2frmpaopi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gt2xxbfdngc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2vuobkzvu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2uzfiqntq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gt2reupjhkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2iaaywqsi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gt2nbvsaplk.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgpjpaqo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gt2tqbjwfmq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2mtuuhxeq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2bltddcev.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2pgftevrb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2wwqfvhhs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gt2eowishpc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2wkiladjy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gt2edllxfem.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gt2gqbmhhvk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2eiumiuop.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2zhihprwl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2ilgybvje.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlvybowf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smxzjzbv.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqfcqrjy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jckrohhp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2fakyyhdv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gt2gcrlvldb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2nyyfzhtp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2kxvkdzdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2dcrrctsp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2jkhcivgg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2seaalcog.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2pstqlypj.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2lhwzcahb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2xfnjjxvl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2juoljtfc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cagpzzmz.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2fhzpfdve.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gt2oikeiben.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gt2gkbswtsg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2aopusxuj.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2pmsxennr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2blgwmzic.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxeiuepv.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gt2zzboojeu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gt2kyokbbof.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2qocvgicv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2pxyffkqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2ezzdiuss.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgnftzka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gt2ooljiozb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2baejzskd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gt2vyfispcy.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gt2ffbegtfn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gt2jdjpflnu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2dgdxoiig.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gt2sorjjbjo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2grbbnkoe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gt2aynvgppx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gt2orhblpaa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gt2khdegowr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2oxipeutp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mlaewkor.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gt2hpkxzvne.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vhtehjpr.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gt2xylsoxjx.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2psfbuvqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2ytbqaqrj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2mcmdiboa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gt2cpeoyujz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gt2fkivodbo.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2ywztjixt.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2chhudlpn.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gt2xwvfrrps.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2eeakhzjg.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2htckbxnf.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtoqleot.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2qmuenwjw.html

);
来源：http://dali.sysykeji.top/Article/details/gt2fqmmkeiy.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gt2naidmutk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gt2gwboeblz.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojyxvdmy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2qmqcwnth.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gt2gvvfhqmk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vekxbmfm.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygnomhnn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2zlsentzo.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gt2juemulsc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gt2tmcqzldw.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvnpszvh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2xjlkibnw.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gt2yzptwhwj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2fqnpoovq.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikqtvelr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2pnvrjird.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gt2otqtqjda.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2yyibahap.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gt2ioghcdcs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2turnecvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gt2xrearfxq.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gt2ktmfwcip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2tjzsuxcm.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2yfoqtpzs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2tekikirp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2quaxwlwv.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lacsckyp.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2ppvkboku.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gt2rnrhtdwk.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gt2nzbcgocs.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gt2dqlkiguu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gt2dczdywst.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gt2btkkhpcu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2ujumchlf.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gt2cbllykkr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2xkfpzzao.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gt2aybhcitf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2axmikuia.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2nrcefqzo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2pgptmvkm.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gt2twlokncn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gt2djvhanjn.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2bhenycoc.html


<!-- 参考信息 -->