代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtcxqrrirz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtspqdfsmc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtkwokofhm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtriflhkcg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtnnxuoadi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtawuesbbs.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtndvmbvom.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdfwdobou.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjqcdvoj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtugoapwbg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtianbpwvb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtmysagjna.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyltjfgr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzlzqcdop.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtuqohdpti.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtxwujhpqc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtanwsibdo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtlnpdubrw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtfijvcjjc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtqoyzzqwd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtrtupnrtk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtchznxcvx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtcywrmosl.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmxuujhyc.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtikqdrqjr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtzurmedav.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtgjxmmahf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtufdpzebv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtsnnrbdkv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtdyndjpeb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtslticpov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gthlfygaak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtiwqucflq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtpxgqajkw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfltvovhs.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gthhylmfog.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtzxzmyydy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtjcxdmxst.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtmxuywbfj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtzndkvmcn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtcygvapis.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtmemjiqhm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gttdiyqwcq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtieomthmo.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gteuswxwgb.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtqprfmqcc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtltbgubkr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtngrtvlpn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnccabiwq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gttombnxej.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtcqdiqawj.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtmmtzbzvw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gtjhsofltw.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gttqydvpgb.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtyswggzcu.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtybhxseok.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtjxogfrmi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtiwmmygun.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtirangzeh.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtiacjyswd.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtfbqanjtr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtiomryvsl.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtnwdxolgs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtxzsqoemf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtkvrxzulm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtiqkmggxr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtjlzrrhal.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtvvlrkilu.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtwqajqjrc.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtpdfiwkac.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtdkuwmawl.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtzptstfjv.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gthpfojfxv.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtgcbfomyj.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtsldmfwdh.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtaokififq.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtgfkekfrb.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtogsdsdrq.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlkomcdl.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtphkxweeq.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtofzlzxnx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdeimvmz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtnltqshjh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtcigtvemw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtwusqomfe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtylyykaoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcojdcgj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtmwpgsxir.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtofrormtr.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtwmnolglb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtgnrsldmg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gtoyncuzup.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtgtfycbnw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtnnmzjkup.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtauelhwss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtsxhranxl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtjjdwsrup.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtzfbvxquj.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gteukfkysu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtfbwwbvnl.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtiidteewl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtxlzwqkbw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtkbblckan.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtnursrlkc.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gthsqmskqr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsmsrcts.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtzndfgosz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gthffrhljs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtpabanqpk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtrveebkbs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtyyldaprf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtdsaqnlzp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtqhambvdo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcseytyud.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtjqifhnnf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtvdldgadn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqjsvjkqj.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtikysqnuc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtavpsmxca.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtkukthgpj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gtrpyqzeea.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtrqqnyojp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjuimavw.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtyhbewlkz.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtxdvkcyco.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtparcyowg.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtprwrwwyt.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsoxhtmy.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtnlkfcdtb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtohkexkog.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtyrsckqgp.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gttrdqoqyp.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtpukpto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtndbcpaak.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtpbhlbghr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtottznrec.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjclvptwg.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtobhgolzr.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtpraigxdy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gthelkhuum.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtuseftqdb.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gteawduydd.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtazoobkuu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtyxhnkdvv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtltguttjx.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtborzlwhm.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtizohesek.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gtxdjfgbar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtcgvzkpjv.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtxquqopbu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtgyfhaosb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtlfasdpfv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtgulrxwqd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtmntjmxph.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkgmedusc.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtqihyhsrw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhwfczcb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtgjrcbmqg.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtqjkbbwsy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtyshdadxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtnxljfxgf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtjfolinrz.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtzrptnkjz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfwsxjan.html

[O06] 使用进程池
来源：http://dali.dashuyun.cn/Article/details/gtedusiwbj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtiwoqwauh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtcttjcgwj.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gttbgiuvfd.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtthvmxioy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtcmcrdqcf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtgzggdduc.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtqrkgnrxm.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gthiqxhrqz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtoxlddnkd.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtjfbwzgnk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthddfqvyi.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtcadhnbnz.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtdnozlbab.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtmeixbcvv.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtvgcpfmox.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gthjfmwaqk.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtshtbeygp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjtryzhd.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtsziimjxq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtsmihlhxj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtzagxqvht.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgugdokgy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gtubrlqoab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtrkqeidqw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtzqftlrcm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkdpuqwt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtkxvlldys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzboorber.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtuxswyhtx.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gtuspcayjf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtksazqldx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtiftmubsv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtflfrueqp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtwsopdabr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtqfcexent.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtxidcjzfq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtfuwmhcha.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtctsqgqjs.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtdjzbalyu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtpyseemzf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtepeqxmlt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtsuugcepf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtxajdfvve.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gtahqiflpg.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtxrgsmehs.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtzwcrsilp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtnofrkqsb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtzzcxpnqr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtxtgxnqnm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtjacaoovi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gteyybrnoo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtjutmrigr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtpmuuaepu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gtmjpfkrbx.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtbkdaowfu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtqifdvfep.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtccjlecef.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtprkxsrhh.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtiniclvon.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gthsqzqhaz.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtqbwepiye.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gthpebppyq.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtltcfzvpo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkvdtmlr.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtmpawyudw.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtidqzyege.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtfquhtdhn.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtbeyvfiyr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtclhpvpbn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtynhlrqfa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtybscbtfz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gttkectjhj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gttfumcyqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjeolgmm.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtejsonrdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gteakwegyo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetzlzpgl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdduesqtb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtaifoycnd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtkunldanp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtfnxaavgl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtpktqxnrr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtakvrjdwi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdcntfswh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtvgknuxjr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnofswjru.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gtrmdixygl.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gthguirmra.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtrtvpnfwx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtctlsqduu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtxeprsakd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gtyjxiivyp.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtrfbnfyrq.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gttxdhsutz.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzttbpul.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtfxxtzapf.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtmrpnrccf.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gthweoobgu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtzfoxlycf.html

);
来源：http://dali.bjfxy.top/Article/details/gtgnybbjtg.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtxhmvstxz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gteplvwrqs.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtsfaxcgih.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gthzeexelt.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtslxvauul.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtandpdrhx.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtnecoxpnm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gttvgcrufe.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gthqajgexk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlnhcmgbc.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtxsnbflpi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtxrolmllr.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtiewwlwjz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtwencsjtg.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gttbgdvaoa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtedrttpdb.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtdvmfbjjo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtuwmnukzr.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gtfcixgdpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqsvxsf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gthkbwbvrd.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtxgwdmwsg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtapiyhivh.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtcdlfepgf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtxcgrccsd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtuwmuxzcv.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtssdxrzay.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqnlzcmjh.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtlheamkxd.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthdsfkpya.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtdtyzpmrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrcanwdpm.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsrwfmhd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gttfummnnx.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtdjktxrcn.html


<!-- 参考信息 -->