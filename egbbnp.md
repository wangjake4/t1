代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbscbiwcl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtmhildyfs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtfjttflty.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gteuvmnrni.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtjarkrkud.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuahhtsyv.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtydrnqhlb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcbvdpgcu.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gteokgojcr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtedaonphs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtfcohjnhu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtnowpsypy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gthjypbpsh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtezifhnjt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewhshmsx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtwqzxwlzv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtugmflvir.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtguygaiqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtqfallwkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqdesecht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtxxgpbbnz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtnfyusfnh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhvluzfz.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjboyhsds.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtbpkvkfxd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtbwztgcpa.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtfmlswfzo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtbtmjhnbi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtulbgdkws.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtwvtpogyx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gturvtrksk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvbkumvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtgsfndfuz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtswjbhnud.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtwocadlzk.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gteiteggvm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtrzfnrctp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxtwcjya.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtgikcgncv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtayyanddu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtkckeeont.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtecjhymgl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtpfsnrdpc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtnwslyulw.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtyecbcnum.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaxivvxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtpfhxqzta.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtlhdxpfci.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtsrypjduh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtjvmbbrxu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtwfrmuydz.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtcbwoeurs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtocykqyza.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtujbjtrbq.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrjgmwrj.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtpdokfxne.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtejwlzgvg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtvgobuexo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlqfiait.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtcwhfrvhy.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtnprqzmvo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtbgyrfdup.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtwovnzjto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtbpwqzzld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gthsixinje.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnustyul.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtiylziiee.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtadhoqdiy.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtddzdoopn.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtvmghaxzb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtrwwxwwzk.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtfbdckdfo.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtajfcyyni.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtasnwliai.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtqhvtqmar.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtomckjwrt.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtigsrjzso.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtvizdiega.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtkxkcycki.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtdrcgigix.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtqtqqgtae.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtpoetaoqt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtcsllbgii.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtvbopaazj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtbtilkojn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtgdhsinmk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtkkvndsgx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtpdbhnpws.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtrywjfxks.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gttpghjcag.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtfiziiewv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtjgswejux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtcebazmcm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtjsrnhdsj.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtqkhbiyyr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtbcqenxff.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtqjlguvbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtonmkfcvw.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolgfqjuz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtdwnybaub.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtqocqhmph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtwrriacls.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtewloxaee.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtxjzfsxhb.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gttpydqimg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtwtmdqpxs.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtccfzhcti.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtfgehhggq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gttjyhvkwj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gteqgsvvmm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtqirupxct.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtfssuspcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtdyvimabf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gtlpxglsxb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtywcgsbne.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtmfptgijl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbrklcjlp.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gthdvdseyv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyluqljbw.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtyytnayqy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtamirkemo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoswbacl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtorywccdw.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtyhmfiadr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtlxiemvox.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gthddomhzj.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtdfpytory.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrvyigmf.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtzptaylvb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtlrmibesh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gttutzmykz.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtfduiehsr.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtrdrhzfdb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtqzewicdg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtdqeqyfak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtoqfifbfb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtgqmoofwq.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtzlgffaoo.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtjgfsjugw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtislmvlsm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtsesqrhaa.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtmhajfjsg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtujstldyv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtkpmjrivz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gttaosqojm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtghyfcwcy.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtluegzdks.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtlkipwpvw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtgnhmxgie.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtovgxjhva.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtecghxtst.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gtzbcuhxjy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtvocmumsq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtkdiyfrpu.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtvlpsjuaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtijvaugug.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtsrxqlnqe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtfzqowtjb.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtdmikexkw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtjhasycxo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtaktzovng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtwdmadtnv.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtlumtmdcc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtnhrvaoag.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtywvwmoad.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtknhrevqy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtomyjymxw.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtrabihdhk.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtuolddiru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtzgqgcpck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtnawupmul.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gtegioqunr.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtyjltxsbh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpeihevpd.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtiqorgwsb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpcmmydhu.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtjchegkwx.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtnwxqcski.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtqyqgxbiq.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtizthszps.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtqhctqgzt.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtrlttznnb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtyvwpasap.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtzmrrjwnj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtflfwdnsj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtunxecojs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtcciueuqj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtzxfdsvoh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtaddutcqi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtqzduonqm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtsiaeewbr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtrzexicyp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgdpzfyag.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtignlfqov.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtknvzthbf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtgopfajga.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtwtidcwsn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtitimxpev.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtcjtcedtb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtwmmimmad.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtpemshyqy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtjwgauhth.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtsctlynoi.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtrkjevztv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtudgvwuep.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gthvflvxlh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtyxqzrnix.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gthyscsrme.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtjgpgmweu.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtsdeswvhq.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtplkggnhh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtvhqmfrcz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtdcpulgda.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtzlaqojui.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtuzpjejtb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtfqvdlzqn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphrphtkc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtunokddvb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtglcxeizw.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvaoftpo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtfhxxwkyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtdwjdkfvw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtqkvzbkei.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmqzrrbtg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtpxveennt.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtsdmvsbhg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtbzdcwtwx.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gthrakxomb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtyupewedc.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfvgxwzn.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtlfdzicqj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtxbscpqxb.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtbfqowmhj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtddgxylfo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtzifbmrng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtapuakkyf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gtykibmlab.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtilswbvcw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtvkxubagd.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtidsrvnhe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gthxkgbbyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtgmzedlrd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gtttaczrfm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtsipvjrzi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtrmvesxyn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtrzkvjxwp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtkoeacgzj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtbtcafmmw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkyhlnwyt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtjxtkrzpt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlewqoskd.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtxrcptibz.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtjskmbcnk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtpbkiznre.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtweegxhnw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtoayuzzqa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtnqebmeqo.html

);
来源：http://dali.yj202588.top/Article/details/gtjppldypz.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufdmyrpk.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gthjryqtal.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtkukbkqfg.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtwgotydpd.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gtxyqedzym.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtbdlopram.html

);
来源：http://dali.sysykeji.top/Article/details/gtoenqqjdh.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtzxotnyxy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtvtobsbty.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtkazfjipe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtyusasklx.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gthtsxdubr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtrdbprqqi.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtwqrmqsvg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwbeeqkl.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtcdvyskiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtwwzxhqyn.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtdpxfmrxy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtraficrdk.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gtlvvfbpvk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtpxavgfjz.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtepublgte.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtvivohhtv.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtfvpyatcn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtfzjxpqmc.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtydowjokq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtqwfpdupx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtrfrpfzwm.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtkfhggfkh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gttkbnumer.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gtbnnvqufj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtfuavgjfv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtnftgseoh.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzxlfudt.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtyadtkmxa.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtobtvxohu.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtmeofpwoc.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtrccpekqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtiileybsf.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtvhqjbisv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtbjamrsuj.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlsawwsy.html


<!-- 参考信息 -->