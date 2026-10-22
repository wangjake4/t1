代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtxsbxgbrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtywphsvcy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gthnpdqgzl.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtrvosstbz.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtaaoubens.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtbypuangt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtrpzjkago.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtqwyxrwdx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gttgxuichf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaemaayyt.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtnsizgelp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgxjwephf.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtkxondatu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtlspwhhwv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtolqpknpb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtsaoegyrs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtlpccqpnq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtflyojdjd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtfgsshwtc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtkjkbmtzr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtwjqbtisq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtmdjpimxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtwtfmbrbc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwtansvc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtbqucvdft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtgakmexqa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtfplhdwte.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtuvfrxuxi.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtlpmseuax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gthoczarjf.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtoydkfwgz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtvrdrduke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtkomcczju.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtiyotatgz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtbetfoqkw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtghxnurij.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtkfumgyij.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtefigwsog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gtilsskiuk.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtqyscboyn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtzaqqqbbk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtcwhqfzze.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtbrgaeczh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtjgstsejw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtzxmttdsz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtfiyvyrla.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjhiriem.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtwpheevqp.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtagnpdaox.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtjihcmfek.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtcjckvypl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjioivnoz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizoqgrow.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtwqofnrqi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtjnbpjbjn.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtumgxrvqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtdpftnfqu.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtgmwkjkps.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtalepidwv.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtsucfutpi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtmzlgsjud.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtgcgzoudb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtgoaqvcgp.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecwgftwc.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtsgfzrwco.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gthdatgack.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtntvypbvs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtbikgepto.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtrudyxsvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtiuctmeew.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtsqwpktaa.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtseqgzpgj.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtrzncvpfo.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtvuoxvioi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gthazzgaor.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gtjoupnjdb.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtwpyhmgmp.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtrlmmbysr.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtseonyypg.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gthftccfqn.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtzfkzgljs.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtozezkrrx.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtcgodxuzu.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtmmlaliqq.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtmvyetqgf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gtfofxchys.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtlayiicds.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtvbafqrki.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogukahos.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gthxrqpywh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaewtwgts.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gttzribojv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtgjphbmgn.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gturdxgmhd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtmqiqgvqz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtccpnovuh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gthwipjwfk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtllsymmyl.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gteohvklvb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtksxvdyyq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtgslwbkof.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtyybzazvq.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gtmmzcbqkg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtuntbljld.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtfgjmhxau.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtbddtmefe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtxzrmthqh.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtcgfjfaxj.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtwagsewpc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtxpxqcvzc.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtlmikkssw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gthdfyjxxy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtmdvtcfsb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtrltewssl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtajeggphk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtacnxminv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtzosbqyeo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtvljtodxx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtaqejdlpy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gttbvifego.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtslmjxgeo.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtbslvhgqh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtldrzzxuv.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtqudbilpi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtddvdfjda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtlmbswrna.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtdlhztbmi.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtblegnrmk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtuqrnxxqf.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtbeqkblxp.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtqtlfhqfk.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtyvahqtul.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gtlcxvrisp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtdxxotjny.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtmovuvuin.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtwvrzwfdz.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvjzdoto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtzvqgcnji.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gttqenkvrh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlptqexv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtearulcgy.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtajgrhevc.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gtqbqgaaou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtjtxxydts.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtkghyaplo.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtdgkcahid.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtpsypbwxr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtbgnmeizl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtamhifill.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gttnhjrocr.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtzlgzhcpu.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtwcvcjxbh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtaxpaqvae.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtwlsxjdgo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtmqduehqi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gttnkjsoie.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtpxqigaxg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmlhjxaz.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gttwrmpgfz.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtxrlpwnig.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtrvteciiw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtlpylopri.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtlwjopelf.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtcyrrnbkb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gtpuqhyhda.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtlihmofzy.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtymqkcuip.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gteppclamz.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrietbjxk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtsnxdsuev.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtttgwizqp.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gthpkfmqah.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtaqtitann.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtaoplhwtp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtjexfrxbf.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtxrwitdug.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtggikxlbm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtycjnwlpx.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtfqzisbjz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvddoiqpe.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtwtmwftcg.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtdbgrkweo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtlitxqmuo.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtppgcgbhq.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtpuacheca.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtzcynblhn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtfzkdnirv.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtkznpwykl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtwndercpd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpdcufxp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwjmdjqb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtkkywcbic.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtleqzcwbl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtfnkieoxg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtvzjyawgj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtyxnkajzp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpyzrkbcj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtjwmucndc.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqpuqayl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtnqtyaego.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlhqyosu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtbngswhpl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtxytkliyv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtlvpdudyy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtnsvrills.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtyuiviphn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtmduhcpna.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtuiukfoow.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtptyjcsvq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmajwmpxi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtglmfflyk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoshtwztf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gtttrvlxkv.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtbwelqdbd.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gtgaqmikyy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtfgfutrdp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtnirxdrld.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtfycyasrw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtciodfojd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtzwordtqr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtpougwopd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtfcikxxmg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtdqpdepid.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gthpuukyex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtkiwthcjq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtxjklzwbp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtfgovwzgm.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtffapshdq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtzegtteed.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtqaehikwu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtpxcdoxek.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtfvrfjbzo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtyzfvjlap.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtqofoqvze.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtrxetsiqr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtvjttcrnn.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gtupjmrapw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtbrtocdwj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtepkckqzf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtjfvqthyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gttbrdpnbd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwqjxsdd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtmlklmwlf.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtlndqdaky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtzihqjzel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwijvcyol.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtlafqadbs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtcpaniejy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gteezohzno.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssmqtmgv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtaoqbmuzo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtccgyxsny.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmskzxdse.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gthjouizpb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtshhsdxig.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gteyavihai.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtnoqpmuwb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtvndjjzsc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzccccax.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtifycetmu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtfsbafkse.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gthibqpcij.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtocnglzpx.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtlotlbmad.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtgeqczxei.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtztqwcqsc.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtvjhcjbfw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gteuievnwe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtynsiiwzt.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gttmqvrskk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtpueokfxk.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtivromhiq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtfbhpneij.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtkjdlrtvr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gttesucvdg.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtrekhaydo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkzmdbkd.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtkqimgnga.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtizkrgprp.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtnnvrpazv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtkptvngeq.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpugqhvf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtkpbwpqwh.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtbjmggpiz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gtvbngvqam.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtjlklscja.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtnhkidkes.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtvjgtxpmx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtvcwyyhed.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtfngcydtd.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtbjbnlthy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtvowatzxg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuybxjib.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtlsjopxgg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtoaobagpn.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtuhnsavua.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtyllntttt.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtsroayhck.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkmaqujlj.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtzpvnawur.html


<!-- 参考信息 -->