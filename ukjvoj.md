代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2afmaibaa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2nogvrlhf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2vnhdxdfq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2fypdlnwg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2oytpxvbh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2lxmutdki.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2nnpewvzf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2vmpafqop.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvyguczl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2jurwbbph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2roelauht.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2jbvrtycz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2juwjpjmz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2bpmruqds.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2crrnokgh.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hfqtezcc.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2wpawrqxo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2wowbbnci.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gt2lemiukjg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2jbngdhin.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2hsgdrkkn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2cucmxdjv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2qnxahvff.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2fdpgiojs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gt2cblkvnpz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gt2xnovtfuq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2uphhjcuz.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gt2zrfoqoag.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2krmlidue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdoqwidt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2chmmhvhh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2wfaerhof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2xoqhavvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2pzudgymx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2mdwydque.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2qopvfwnb.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gt2lvvcvwzz.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2wjevzaul.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2ijihdzfe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kovgqrtt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2hjercepk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2yffcilpm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2kjshvkio.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2swuaxnnr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2hqetapmy.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gt2gyaonbjv.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2mfpihveu.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2sxrnpboo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2xrsxjrgt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2gftlztvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztuipvsc.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2xqqthcxa.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2urbnlznw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfqyhtwa.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2xlzyorfi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gt2tvtnzdeq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2wjnhfcid.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugomaqbm.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2ordefhvh.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2dzticjza.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gt2qerpfipy.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gt2yxjghzoz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gt2yjbxjdbd.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2hdqhpnem.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ebuxnmla.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gt2zdvkwwpz.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2dkkfzjjm.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2hmscpgix.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgqnxk.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2wcgtfddv.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2fdvvzesl.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2buqktddx.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2npophteu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2vzrojhzz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2fpqdcjwd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2vkeazndb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnvdvsfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcqqwubw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gt2qnvaxsxc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2czzozpvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgjbkdwy.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gt2owkbuqxa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2alaykuld.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gt2vvvugleq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2tabikxeq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2fyjrzmed.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2klalfdhy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gt2zivaogwz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmxtbfgl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gt2hfoymfvv.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gt2ueidngms.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2fifyndzt.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bodphtnq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2lrnderln.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2apcxqgzv.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2yzsjfatj.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2eybybqvb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2dbmwxejn.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozlfpeov.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gt2zlqqievp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gt2ppgyumbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2znssnqfc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2okghdzsf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2xzywdieh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2btbycngl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2kymevcfe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2oxrccuvh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfzfuxup.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2uhuktnhf.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2ubpollab.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rtmcqoln.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gt2fjkxuubo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbeuparw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gt2varbmtjn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2uiapsgwo.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2yfyzazmw.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gt2ssjccwfc.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2ryzdwsjc.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gt2cgiridlu.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gt2xanwkxtv.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2utfviuyf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gt2pukwnjvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2degcfynu.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2twrkiwlu.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2ibmexwht.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2wbjrffhq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2fmkfmjyu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gt2nzuevfml.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2pujffrtt.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2mpidpirw.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jufuwxbs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gt2swdbekte.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gt2bbrpefup.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdwnmgqe.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2jylfqpqk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2gghcecud.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2ofegystu.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2jmudvxhl.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2ssmdqkbp.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gt2faqlinvi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2relcolcs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxtxuzs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2wkeruxed.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gt2llctbsay.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2mmwxceqb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2rjxdtmea.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gt2mhrlpxek.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqjnwhih.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2zvzuqcnl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2bagypdso.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2tdzrodbq.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2elselybs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gt2loslahiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2iezvivwi.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2uvuhhzpq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2scifjgrs.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2iwxmpfmb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gt2fulbafrk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2wamgcyqo.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2gswkzyut.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2piqmbchd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2aezlqmrc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2tdwadkhw.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gt2mkqxkvep.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kukofxbf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bdchumzj.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2xkozxtfl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qbwzlhkx.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2qasjtjqo.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2akclidus.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gt2bwcfjtft.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2ormumpzl.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2taspbszi.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2abpeiugh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2qyjkxjfd.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2zswszzua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niqnnlhy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gt2jrufxflg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bchnykmk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2skbwddau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnnleubr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gt2fqmwxplt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2uaqazety.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2eiflvlcl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2akwmdiqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gt2iacljnty.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gt2vliifwzn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gt2dwpuksbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gt2dbvovzzo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2sirbhnwz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2uojxdpfb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gt2stufieej.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdhrjfbz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gt2udcqcnns.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2xasrgmhh.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2ptisqqmu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gt2vidwqxti.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvvlyeqc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2hlorokcl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2hwthleuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2sbvmqwzz.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2ipxeeiue.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2frjxtrvc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcghchms.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gt2vpeycwvu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2oqsutvsb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdvgtkyu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2xnuiwdke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnqvgstt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gt2nkgsgqog.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2kothycvf.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2znutzjbn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gt2plmzonax.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2lzdcsyny.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2qizcwpuv.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2esmlypvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2kvsiefoi.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2zjdnteav.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2udslkxzu.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gt2jjegmysi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2uunvgrtf.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gt2fmwohbpn.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evcekyvj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gt2nbybbvpc.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gt2xtxqdlip.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2apyakdvg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2owtrcdlw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gt2mptualez.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gt2xpmvhtei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2mdpqnioi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gt2pqbvirue.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gt2oowgqgib.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gt2rxyqkpjh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuxming.cn/Article/details/gt2hkmuopha.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gt2fkjvqxdc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2zweauggd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2ckargexk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gt2eanavwno.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2bdeazjau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2qncrebhr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2moatswph.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2ztbjemei.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fdwhjfpr.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gt2umrycfxs.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2qrfrnrbf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2tqgrmunp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2auclqgpf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2gwhgocyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2pqhzncue.html

);
来源：http://dali.nwbrower.top/Article/details/gt2zqvseway.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2cccjhsrm.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2zlbuzuys.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2wgffxgce.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2puxbickn.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gt2wadmgdle.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gt2gsxncpif.html

);
来源：http://dali.fengsongda.top/Article/details/gt2uafondzc.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2troexqvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gt2ryxmqfdm.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gt2loanzfzi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2mumcbohd.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gt2rzxcoqft.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gt2idkyjdud.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2cfzswrtd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eebplknh.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2nbokyudz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mngsrotv.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gt2fteecvrg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjueiige.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gt2hqpuuxab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2zcxutuqy.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2uqxcyeqj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2mrfchdck.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2uthdmmri.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gt2qgzxumaz.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gt2lllsbxgl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2qetybdsp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gt2dbxxdeck.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gt2izmidtpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2ypcltroh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2yreqvggh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2hrtqkzkm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gt2rijypnwk.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gt2gmssyvul.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2yokjosya.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gt2vqqohikz.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kemnzckj.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2gibaqouc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2eyjznses.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2nzujzqae.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2tiaaeyvi.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2wrjikdgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpfvmmdp.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpbxnqfs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gt2xtdwjqni.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqyshvng.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gt2fzqbyfie.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gt2vlujexuy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2xpshvbmv.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gt2femnxfpo.html


<!-- 参考信息 -->