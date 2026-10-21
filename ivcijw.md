代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtwjbcnabx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtktdsbdfc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtkoozldgd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gthqswujwf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtqqwawbwo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfmlmllum.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtokwrkfyg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxjabfqmr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtmbngianv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtimpdxfhh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtyjvewwql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtmzywodge.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaghijgy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtuklsqmpp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtskbttpbr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gttmgjecpu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtwzdjjmvh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gthjevorql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtovyiklsu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtrxiicaxa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtsrbyccay.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtcdollkei.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtvefgpouz.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtiyxlprdp.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gthdtrkcez.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtmgckkagf.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtxyyupetd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtbszihrrs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtzdlszwnf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtijqfkxdu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmaqseai.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtvlhwbnbc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtcxpdnbiz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gticdpvdji.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtqabjlzpu.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtrdvutong.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtqrdchjfi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtcsqrzeen.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtopdufwpw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcwfjzry.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtbijrisvx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtnqyayioi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtsmeanvwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtgvnlaagv.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gttkucxxam.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtysqyaiip.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtfptjvwyh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtxcaffkbb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtxdhdyxit.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtrcxggyix.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtfxmfxkcd.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtposknfku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtlbairbbs.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtjxojgrak.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtgvevqqxg.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorzmdvzy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtutjzpjuj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtfhbpkizq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtfmuprcbz.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtfoaekhgf.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtexurdtav.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedvrthny.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfcqsxxl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtknnbirso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtsxvciouq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtmhfntzsg.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtmhaycwii.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gthlkiheis.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gteizzhros.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtykbmtseo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtcnjzyyxy.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtkezyhcxf.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnrhdaqd.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtitibfdab.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtdlssbzdt.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmahiykwg.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtspcrqmpr.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtyutelgow.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtfhtsgtfz.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdntqexdx.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtlfwrgcfy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtyezdktsn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtkeimxhji.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroxjvckj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtwqixfqdl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtvwitwzmu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxyclmxn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtzslkcjcj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtdzqyvmmf.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtfmjrjkqn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtfdionmqg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtlrdgmddo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtpopoouni.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtjrzbyuwf.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtyvkwkmzx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gthosjofyy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtrjmzcjlk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtjbzznmii.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtuapzgiei.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtyjvfdhok.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtknelbhri.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gttcttflor.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gthxslkhbb.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtfozimvjl.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtdrplutzo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtirzzltka.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtbcblakhv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gtejikxkpw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtqdmfgrtr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdajdgmj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtipagkltn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtqayihykc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtokckmkup.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtqalejyca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtcxumqxle.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtrnceipcg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlnchargh.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtybpolods.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvryuiaca.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtamqpfphv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtdyppvbzo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtbfngmzeo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gthxqcsqyl.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gthnzxwcus.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtzvlxvveg.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtsprqyroc.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtkbuqochq.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwyowzau.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtujttdqpu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtrlppmkoq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtqtgazxjf.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtuxnmnpro.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtxmydltlu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtaepsmomr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtuaevzvqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtywpkagmm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtemhuojyo.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtwbfpbseo.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtvvlzbfcj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtsqwnuncl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtqmbguqex.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gteukaejwc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtgnmyzavb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtqospqzes.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnraijwgs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtnvtnoitz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtdttskask.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtwebcqimd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtjsmkjvnb.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtidkfespa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtfkwgukln.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtmyaefdpm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtlyimldpk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtdyoerefv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtddcborco.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtbbnhmsfk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtppxcliqc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtrtqdlzui.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtkxtatvyu.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtnffruhvw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtoprjlsbz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtrejotgib.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsykdatv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtvshzvpvg.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtyzueilqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtnoguadir.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtiyoqsxzb.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtadfygjfp.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtnwpglxfx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtrbaghajj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtzvqiyeyj.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtsusyaond.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtauzpehfj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaezbwkkv.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gtvjnyuzei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtodihtbek.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtorwmcxla.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtkrokiqmx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtltxxbzsw.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtdgzrnlwx.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtxmxbaruz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtaagqqjpq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gttvyemaln.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzdpqjyt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtqocflajv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtwmucddzy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtrxqwdcki.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gthktnslue.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtchjnuuod.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtufsovayj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtakiqszgt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtnrhrkktr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtozotwsbd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwykixkgz.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gtzmviuyxf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtbmtzssbh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtkpeagpsk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtvscnakre.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtujnnmwql.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtsrfvgyio.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtlwortopd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtzuhxiimw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtobbtsckg.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtpauzmbcz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtadejdftq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtdnasxwxs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtlqrajzjl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtqfejqijo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtsqcuayvi.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtedhbkrlc.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtfyguaist.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtbzgnwbga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtthvfvsoo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtmutwmjsd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gthhyfzybf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtddbraoes.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtxlcmyfyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtiwiidrae.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtfyhestgs.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtgfclbeqr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtjrnnnngd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtshimwjgp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzcsakeo.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtlfxboekr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gtmifjjsma.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxddaptux.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gteehxdbfc.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtugplppvr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtiejvnoxo.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrraovwka.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtpauktmae.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtwuhzwmnw.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtnzqochyv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtoeygwkjl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtcrtvtcpe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtjukuqdtu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtidgzrjjj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtmdigukin.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtaqizuhka.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gtaztvjxmj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtdgjsmcsp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtlkowcfrp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtefatvdlb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gthraksvvk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtpgtkceod.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtynlujnjk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtbqlvsngs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtnmryjmyc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttkmxekbq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtjjxcxxhx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtslbxogzp.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gttroomgwz.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtqqoidogv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtztsemhyq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gthjepoklu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtvfakeukt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gtqffunrxn.html

);
来源：http://dali.meibo888.top/Article/details/gtxmfoajgv.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtrtquyvgf.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtjxxprzzr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtmrrjvbgb.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtihfwfltm.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtllkjmpts.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtoqalqxbu.html

);
来源：http://dali.meibo888.top/Article/details/gtyxsfldbj.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtsozkhknh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtxjnaiqgc.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvhfcxja.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gttowxxdlm.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtegoyqzuy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gtuusidefp.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtunznpylf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtaywbqhaf.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtbkdawnnb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboxuacfb.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtoamhbjtq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtaevvjtdc.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtsxxxddou.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtgesbfcij.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtisgjzvad.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtofpktcij.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtkkvkvmio.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtemhevgle.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtkvghcddc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtgitdudev.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtjlgjvwqd.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtoimisrcs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtyvqmcsri.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtdwpzwmfr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gteeyxdszp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpsarlnb.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtwvvnlffr.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtaoaaekep.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtyhundbjn.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtpbpcuxco.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtnfxtfhnr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gtphxbzsuo.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtupjkxbuq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtodtztltm.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtmabznbqc.html


<!-- 参考信息 -->