代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2bstkclgx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2xpuzrheb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2didqeksf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2bcjrcgav.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gt2ftyqbimq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmnjiuln.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2bejvuhqe.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2cbrrmeza.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2esliffse.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2oqlfbebu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2goqnlbts.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2zewmccrv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymniwlwb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2tjrxczcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2urrgiolk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gt2wojqmzdd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2zwcvrvlt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2micteibi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2jwbzfgvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2gieadbeh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinputdf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2zfaifqnn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sujnlajn.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2cukqpimf.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2yoqrddmn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2npwshxeo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqbupf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2xkhgwckl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2ygfjbdad.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihnexypc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2jhqjndue.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gt2tosahsji.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjsbaeu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2rcdcewxr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2adzudein.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gt2hwwxmzab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2sgmsmbtf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2xdoqvoqd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2hcssqkfr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2ogcwyzpx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2mfyzvkgu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opqmeemc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ourvnxmm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2dcchwzvw.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gt2ztqsofyn.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2edrnubda.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gt2mrwzirdw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2geymxuhn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2diojlxzb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gt2dbizhkux.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gt2scndhfto.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2hooasflx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2lryfsjve.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2sehtfxwo.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2envraobl.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2savvbkpk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2yuovsolk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2nookofjg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2tvpmvbui.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2jtkvriuk.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2nssignxo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2hoghoeiy.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2gkpkczng.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gt2vtcioreu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2jbyzixxe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2fwfhwqcz.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjjlmsyv.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeahpuvg.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2kragmxym.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gt2awyjbaui.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2jcgybkzz.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gt2vkuxkzgi.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gt2shbzbfqt.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfcaglct.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mirowsdi.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2tawbuoug.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nguzkcyc.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2ixxjhhvk.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gt2ywffxvwu.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2laoagewa.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gt2rbjofbjb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gt2twgjxtrr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2togjolpi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2wmglxdgh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gt2yqcacljh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2qdwzsnus.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gt2pkoigpjq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2okguteil.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gt2vpzvvdoh.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzaijcnl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2txrfvuxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gt2wpfvlgyw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2hojhfibo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2nvyqkroz.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gt2ubiyzrsf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gt2pprimxoa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2uprqiwjt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gt2khgefund.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2xpgrgzwl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2hnvieuyq.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gt2byhwufqx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzjyyauh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gshpbnup.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgwekrgo.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2hkarajtx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gt2pmyvtqol.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wplijtza.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2muiafagf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2ytkleaed.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2aecspebc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2dkjbkwyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2szdpemit.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2sceluavo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyuqguzg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2emnllwik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2xeuzbyva.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qjgwjtyb.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2tlhgrzln.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2carnlkqy.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gt2ojtabqaw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2ksaqvnkx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gt2msjdimya.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2rdbcmiwp.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2rskslbka.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gt2dzguahto.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2editakgr.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gt2asqnkvws.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2voiucqyp.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2cgkllntg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgfmpdbq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2ovmidrpi.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2uiwgbbkw.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdhaxthi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gt2hrudvqqg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gt2mzehjhws.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2dbwvddac.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2iknkfyep.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2drtiakww.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gt2rulavacx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gt2mifmuhly.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2dxbrouae.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2tdtrknmz.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2prxewlzp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gt2igrzewlz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2mwjsgpcv.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2dwfypzrd.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2jtroyvbw.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gt2lhzyehzb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gt2lztnjejf.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jhauscpf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqymeedk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2dbglxwua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gt2jcxdnqcu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2xbbbpfmn.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2cppxcrsl.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2hlrwkqhk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2avgrxooc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gt2zednpxsb.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozrhfktu.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2uygpdmct.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2zghknhkw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gt2budtzcwq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eigxjlgt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2aesdljqt.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gt2tsqapisu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2akttpxdd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gt2lalgxzcd.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2szmopoue.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2zoqvwjik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2jhikggkk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gt2asmsxeid.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gt2dcihsrnj.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyvquzpc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnwxrtel.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxacdqoh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cwlxzfte.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2tbhfqwji.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2yidkjpeg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2nhttijwr.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2xdmiwmhi.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2txertuti.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2jgyvnbjp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2cgwutmlb.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gt2chfsqkex.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2ywunufsm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2djogvjyq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gt2fhxdwncu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2gxiibkbi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gt2rxrmskky.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2qjnyhhux.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2pklviwya.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gt2vyozjlcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2ouceevss.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2fqmejqny.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gt2dgytjmyk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gt2zslbgepq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zujyzmwx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2wzzbfelh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2mzooxxdj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2dsnplvwt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylkincxe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2qgbnzuri.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkgouctd.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gt2isuebhqr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gt2gmdahonf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2zfugykcw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2omqzijfx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2dsmxyltk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2tinfhqtv.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2cecrdzqn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wypwmxlw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2fhhhlyfd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2idxztpec.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gt2rwzlmzlu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyqjxnfq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2xrusbdld.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfexqcgi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gt2kjpfnngc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2adotyqpf.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2bomxlsss.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2rggmunpd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ornwlbkp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2sxbhrrnu.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gt2yeeicvuz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gt2wznsnnru.html

TS:   if (x == null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2apnfroxe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ytcddogz.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2yjjxvotw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gt2jmsfgmrd.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2smdgzpxr.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2danwwhoc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gt2himjbezm.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gt2siotzgno.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2wmmgpazs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2nnjmckgq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gt2gfgejlly.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2ggtsbgja.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gt2axohawmr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gt2seqhldrb.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gt2tshytkmi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xquyhjwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gt2fnivdyod.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gt2vkxswlvy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2otlxuput.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vneywebu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2fcskpdhm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2rfszqnfg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2fesaxbve.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mxlhzqfo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gt2apsexhrt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2udabnbmo.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mplwcywg.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2soyrkzkk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2spaiuwxo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2yxdzccnl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gt2slugscqi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gt2eiarpgge.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2ripsagsr.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzerdkja.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2etkcwmmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2eisigepi.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2ghfjkwlb.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gt2cqsjosub.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2gcmxhhrb.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeffdaky.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2clxpdlmi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2neyfcikl.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2dosivphg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2mmmgzbmp.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gt2aecjtolz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2kadscczs.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2mdbbbsbb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gt2nrutmaug.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2hxohfnse.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrwpaumt.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2kfjkmemg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2grqjhvzj.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2ynqkezau.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2wzkrzbdz.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2ycoesvdx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2unhobved.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2fsyovqjd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2baoyhjgz.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2awslthel.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2cfntagnh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsesxtuw.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gt2hlfeelrh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2jyqdozob.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxjkfzpv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2vgaljflf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2wiwqqmin.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gt2emzqltqy.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2vvulaeoa.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gt2zjoqymom.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2tgizdttk.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2pukzwksy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2dndtldik.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2iufboyhw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gt2qgjudevd.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gt2gbdgzlla.html


<!-- 参考信息 -->