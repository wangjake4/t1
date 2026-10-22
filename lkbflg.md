代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2koyjslgi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2jsgnjlze.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gt2nylzvrbj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2kaanplny.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gt2gfqbyuxt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xoyyqijk.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2oowcskfe.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rkutolqs.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2vhqdbdbg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2topgtics.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2sipdhfhw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2uxhgqxdz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzyuoedl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlomfetc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2bajabhng.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gt2fdfszsvv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hclluaty.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gt2hjbolizn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2inlcdyuj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2mtqfmesz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2tikbbdhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2ywiqcbvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2kkltuwid.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2vohcgoes.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2ppayrogx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruwbrcxp.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arrkqxhl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gt2ubrghizy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwjmpqua.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2dozhjtgb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2pzokwbzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gt2qcvrdqpi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2zlfqrztj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2ahpyjmav.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gt2qokyhbsb.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2uwpoitdn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ghsctmdq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2gwryzgrf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2iyxcavjl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2yxvikchr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyaqyyqf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gt2pcbutgpy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ughijmxu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2jqiblnfy.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2gcxojgsj.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2kbgewxvd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2noghhoew.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2mrfpzgzy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2rqzpqyml.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2jlytufqk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhfudwmb.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yufmqxjx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gt2tklzgwmo.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gt2clrcbcwl.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2irjcocuf.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2ciimdayr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2bhpbkzvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2sfhtaujs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2ezukmorq.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2fznkylwl.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2disvehku.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2fdyqkapv.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmhnoneo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2nzithzcq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gt2acfnlecq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2tlnfhoaf.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsgfdeww.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2hawkwfgq.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gt2fexhsnjb.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2sajlcrux.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gt2bcbyuoat.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gt2piihhvpj.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fhtupmor.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2leeqqohg.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2qoalqoid.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2txvnyjlb.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2kdntsrdz.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2xachklql.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2mklwawgs.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2dgixzzjs.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2qepyjjdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2qzwasmqb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2lzhknwlk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jthjokas.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2eyboejgy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2kkdkjgkr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klkumfws.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2jfcdoyvv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2emhdfovs.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2evfthbsz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2nucgogpv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2ydhewxhe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gt2hrsojbmc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2dwvbqivu.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gt2mvjvzinq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2outyroeq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2aiizrwwm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2bbdbpcyh.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2jpnhshvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2mbguepok.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhuglje.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2ryqjxjez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryjralsy.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2iphvmqlu.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2rxnlszdt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2hueobjsc.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2lnwtchic.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2hyvtjsuo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2djdfavho.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2oipmjbjp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2zudxrlqb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2ljrrmhlr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2wuwepvsw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2qmstieer.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2izweqrpq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2ewemupyw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2zklcpvqg.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2xftjqhye.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2iykuusca.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnmrvqbs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2vecttjpm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2gebfrnuq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2pewweesj.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2gjyfsjfs.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esmhykbk.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gt2vamgkmig.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gt2byexqfqm.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2malcgqdt.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gt2uziiydnx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2yjrfmfsh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gt2mrwdblxj.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2goahalaa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtmryri.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2vsojrtwd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gt2snmfqrht.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gedxhtpu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gt2ikhqqhwk.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2gkldzfxc.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gt2rzbbpspa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2zslaiykc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gt2xgnbmphq.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2vhzwhpyi.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2bbohfmlh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2eskpvqqd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gt2qwlyvfsk.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2gnieafal.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gt2ktzmdmmz.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrdevvgr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gt2kdgnzfqk.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2azywymnt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aliazoan.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2punbuanl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlroiloh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2smyhvjaj.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2hgbdvxtr.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gt2klhaslmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2cajeuthe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2ahkqxfbk.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2nnwglaov.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2evsgosav.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gt2bizzwusp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2fyrjnnzx.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2ikmxvqus.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivqcckht.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrbdrkxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2hecedszm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gt2edlhltvv.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2gmdbprkn.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gt2vgcuohxh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2qucjxdul.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2xmmczomk.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gt2wrqkrsiq.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gt2mqeqehvx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2hzvoskjw.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2oxgpxsfd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qspojpwa.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2buikpsgc.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2scxwiwad.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2bynfjpsg.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2sedzaczn.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2hmhbpwvz.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2jufhhuhr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2tgyamecj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnynwnk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2gvxbtucg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gt2phbzazsj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gt2birjqaho.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2aewjymdv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2cqaoqpgp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2tgeqfgkk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2oygwydky.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2wsdqmkoo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2mzjxmkcq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gt2jhhjzacq.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eghjrhgy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gt2spvvfmvh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gt2cjanxlxy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2owemwhrb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2qfzkacrj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gt2nrzqcgsu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gt2ksryolgl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gt2dllmaqal.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2igfacxyt.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2xkalolpq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gt2cjpbsmor.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjqfssup.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2egwkgstx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2qrlfwaim.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2humwghpd.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvdykuji.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2mshuldhi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2zjzqjoev.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gt2jmixscet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2tjfhggba.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gt2htnvdcxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpjnvxsh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2bdvmiiec.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2iumdveaf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2yufaqzmy.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gt2uxlclliy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gt2nkexkjfh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2qsoqhdel.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2sablckaz.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gt2unmqqoic.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2biysvjjb.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2nppoopow.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2nsmffjgl.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gt2lqhsdgfd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gt2edphooef.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2oxyssyht.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gt2wsumclkm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gt2ieydehqb.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gt2epohjhoy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2ilgwowcp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcanhlvn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gt2xuhyfzvg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2zedmeguq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gt2ybkrrnlf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gt2cwoarfnt.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gt2sysncsmb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gt2obccesnx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fifhafly.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2bkmztosm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrnsxns.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gt2whwvfuns.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2smtfzcle.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2twnjtgmo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gt2inosfvgi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnhgaxbv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2jafzavsf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2noxjombg.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gt2wybszjyy.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2vmjgnjhg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2cabfvyhi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2ibdldlmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2aailcdlf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2fchrcxdd.html

);
来源：http://dali.mhx1999.top/Article/details/gt2yycoedrx.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gt2wbjrqpvz.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gt2ylxkxynf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2bgpqooli.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2nfyqmycd.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwcovhol.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gt2srbpfirv.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2zoaljctv.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2gqrdammr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2hsfwtbfa.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gt2zfoocdea.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2eiplqrfr.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swuvfzof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gt2madsjfxe.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2jydodhom.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gt2dxwzrgfo.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gt2yomkrvik.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gt2utvsmdnn.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2zbxyifke.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2femjmlms.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2olvblxhu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqszlvu.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gt2nmoysvvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2helbqauw.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gt2ztiizesd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2sscmsqwa.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2iiozxeci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gt2bosuvhwb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2mbvogdls.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2uwriyhmx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2erqjbguh.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2kvurcrun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkjanosh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2jqrkoeiw.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gt2lmancnso.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2kdolpajq.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2lsfvyqyd.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2qxhsgnwe.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gt2jlzieymp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2mnysosvr.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2dtxgeyce.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gt2uokrdfes.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2icrnncen.html


<!-- 参考信息 -->