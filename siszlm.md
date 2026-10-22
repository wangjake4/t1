代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtheurczio.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtlcrzdbqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gthmfqkxyy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtvkscprbf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtgfzzqufm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfnmvtjk.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtkyzovadu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxmgsknnp.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtxwweyauu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmssbean.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtkxbrvdww.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtqsjnkjfh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtqckswylt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gthdmfarep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtddckbygg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtamscbhoj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtqzazvunh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtuwqcapwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtyzxcsoqa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtojefwtvo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtsxsfmprl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtgsriorwv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrshazim.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtaiyrggsa.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtlrxpvqoo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkynladub.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtnotabfxr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtqfhxtrcl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtmhlxqiet.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtgltqaemq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtudextcgc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtumiyzowx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtrxxwrlwi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteealnlog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtvpubhbhw.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtsxpnlqen.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuurfotft.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqwiyveg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtvlhxvabi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzficpztf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtfuirznyp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtapewxqme.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtuftpjksf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtwgefdttx.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtqleqrygo.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtenpphevl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtbqbajuax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtxflmckrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtqiolkijw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gthkvsyxzc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtljwvxzav.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtstiehihh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtwetiqzae.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtmsrgcdst.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtpbltglwf.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtcllsbjqt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtganejxju.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtindsvfqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtjwquyqox.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtehqqboop.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtcaclvsvi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtkxvupwrl.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtnuhxmnld.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtqxgrujmc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtvemrrknk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gttkoiyfur.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtvhepafqm.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtyhwmbnie.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtqorhwswo.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtctahwquz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gturfvhrwg.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtqadtbonf.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gtantywfwy.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtiktbkarx.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtntgiuegy.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttdznbsio.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtstwuwoqx.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtagplmzrx.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtnmorsmxz.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtoleehjrs.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtjvzjyqvb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtlunlsvbo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtmjvdxeje.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtoloknttl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtywzbejdz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtxevsfhyu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtzupwaprg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtpaademdn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtcajhoqrd.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtohdviupx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtxyetbkri.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtfjlrdoel.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtqtazvvca.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtluzgwtre.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtzhczapes.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtuhkudexz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gthrqiwbop.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gteldvghtc.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtuiyhnksi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtsoyrwclh.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlgxkwcxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsocxcmwg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtfmvqlmob.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtznfsytkl.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtexvkwqrp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtbkoduebx.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtxcgfpxzi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtuznwhwve.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtoiexomdj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtziaaqwei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtlelwekcr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtzehaqule.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtwqwinela.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtrcaiatxs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtlbdhkofb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtfnadqhgp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtyfjrvsll.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gthdydhwny.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyxdsnvck.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtaiwvgokc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtehhngnin.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfynhqlzk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtdyjcyvxa.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtpoppvfyc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtbvuklioa.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtibmxacdx.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtmyrpbvly.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtdnsghgnq.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gtlwrwlwvq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gtqdjyrhdu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtdyqjplzk.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtbcuekjij.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkhsypezy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtumaodyqy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtqqthksjg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtxkmkvkcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gttycgnnwj.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcjmdgjf.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtlmqmavna.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtjprqeohw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtziwhltbf.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtkuvknqst.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtuwsskthm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtuydeihhj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtvrggedut.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gthyahrwgu.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtzgvmwmfw.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtfwpnwzbg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gttlfvkzaq.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtrjeezvyo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtbgjvzwtv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtnaryrxrx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwqjypes.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtifabmrfq.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtfaawoqzv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtwhisaxal.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtcltxrcof.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtszaqdjwp.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtprrhyaju.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtndwwxlcu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtytyxeqzu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtywfsgwxt.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtxnsrzzct.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtkfvmxfyv.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtdztfowzm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtdcbdasix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtgqcodbnc.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtywhiorfq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gthgfzxstu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtekqhgixf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtkfguymzf.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gthpgoxyqo.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtcfcibnqa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcixgygmz.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtivksxfwk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gteaonerdp.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtfvdpexsn.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtbckdxtvw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtnvsasutx.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtoxrdswov.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtnxkzypew.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtmikstwrr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtaebcgown.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtsvdedbzt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtxgnhpzwv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtvqaujhsz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtbzrjuzns.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gtvaijzblt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtmmkjmxsj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtifqbhgdx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtlrlwzjmi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtwcjyuuqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtyquykdmj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtnehrpeht.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gtzonyyulu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gttjswkecq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtvaadtcei.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjdxfmsk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtvvldrnuk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtvwlyrqwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtkdtqmhxm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gteqfxbjss.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtvcfohzjv.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtawgykuak.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtkclrpbym.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtdvhpbfgk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtxrhzamwn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtafvkppmq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtwblrhiyg.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtdhpcozmn.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtmnoeexxr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcnbxzmc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzyllhkd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtdltxhjky.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtpmpfcnax.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtegghfret.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtrwhzusax.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtmipnydjp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtmllqynag.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gtuqfcchxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtcrodnxde.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqetzafk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtpjvsglwc.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtiasxnntq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtddainnxb.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtqgelpffg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtvwsdyaek.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtyabjquyd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gteoljaeuq.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtkcxlvdpu.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtvueqherr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtobjudebm.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtdmbpfelf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtajvingzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtsovnreyz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtxyjdwbov.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtgapkhslr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtbhqqyqyl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwpitawp.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtivrnrctw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtduqnpjur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtzcuetm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmkdylno.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthwiwfsra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtfniincgg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtiionkads.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gtiuixpgqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gtlmxagokn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgwsfplkm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtcxfrfaxa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiqxfgkun.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gteegnnjeo.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gttxxquovr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtjvhgtnjb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtkfznsdwo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtfankeuvg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtbdoqeetn.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtdgcbqgdf.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtgdejwkhj.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gtslzvulyp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtvcuvhhvo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtgykozldm.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtnmbmavep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gtlcnojlwo.html

);
来源：http://dali.tian-w.cn/Article/details/gtwggfadab.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtozutgmzb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtnnuqpyez.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtqpypctzw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gturcjijio.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtyuicmyrk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtwirbvvqp.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtpqmoqtfi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gteumjfvjr.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtvomvhwzw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtwmctokpx.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gtqdxgjcqz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtygicpbji.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzitjbgrj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtwokjtixs.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtcvivxupn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtptyvdnqd.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtdyphsktt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtgpmgdkuh.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtrsefwtcn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtzyzkduki.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtzniupmnq.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtfmcxrrze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gthkxyzbmp.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtdzuzutvl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsclilisu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtqgsigcwh.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtaaqwnrks.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwyfpopma.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtvnhceyly.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtbzidjdbz.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtguhxoxbd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtavcrwaql.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtgfnapahh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtkgepwjep.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtsaxaidhl.html


<!-- 参考信息 -->