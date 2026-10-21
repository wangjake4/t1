代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtgyfxccme.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllbsxpki.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtzjvrcnvw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttxuzflyj.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtazmyxrft.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfnumjcha.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtwxsqwtgb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtrqrfcjkp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtvsekzwdz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtwjzkhcqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtqmtzqlxz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtcxgimmck.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtecidyqva.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtdocjofpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtvtcsadok.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtkpphanwv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtzwguprka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrrxsldps.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gttvmsfbjm.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiskpwra.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtzysoxtvj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtprsnunod.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtwgbpcajs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gttqhticpd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtdwjditzh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtmwfazmbc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtkajjmiou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtzozdomwl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwispdkf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtgsqpwtzb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtzhcstvnf.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtoigkpauw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtffamnuul.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtmixtowmw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtqxridabi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtceqtbcni.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtgnwobuoy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtesybvkjj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtmpqpzurt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gthgrxptxe.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtugvjvkbp.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtroxbnxyn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtoyxjbsct.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtiglimwbh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtqbxdhnoh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gtjpnlejto.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtbrdcrfjm.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtonnrleva.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxlsmcenk.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtxvtwufoh.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtanlmkmri.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtnxsobcok.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtwaerkbui.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtohdcxbpm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtdjwnfnop.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtoqhrmhya.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtdpfmamdd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtkmstlins.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtfbmhcwuc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtvtwhjgkw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gtvgvuyfqr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtswnecwyr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtnrorhuut.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtbagmnopd.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtefnylwej.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtlftufdof.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtfninilej.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtwlebuuxo.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfqwuzfwz.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtzkxfoesl.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gthcdfahec.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtznqluwwq.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtwhpgahwd.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtedicmmib.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtcunsmvul.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxksdbxmc.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtlspysrpe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtmqgrjvtw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrkficph.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtwhswmupi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtneljawtw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtuohvgchk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtabiimywy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtfeymdxxp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtkptjefmq.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtnyutbrrg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtaitcritv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gteudwkjin.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtthgzyipo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpbjhgvj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtltxxniex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtsxxymnpg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtitdpsinv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtzppcgpha.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtnwzaxqqh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gtqsyncsjh.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtulltpyuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtqxnrtyqe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtvnrfquvg.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gttcxxqnfa.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gteglfymml.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtfbyxcbyq.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtizsqxeiy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtjvhdswug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtkfnufqja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtjlafgkhp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtxpinbpah.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtozfkwxrk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtnnkasxtu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtqmgmjyqr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtdxotrxnv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtystobcca.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtktcfvlrk.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtpgxmlrzl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlyjycpyk.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtigouxiud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtxyrypplm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtuzzacjfj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gttaoqparx.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtufwjezrb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtegnqftxg.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtypvtfnxl.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtxxipxtej.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtntihrdtp.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtglydemxd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkvgbrfu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtwvadixqo.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtdtllnzqe.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtsyowtlhn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtqfwqkgxf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gttscyrkmy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtrohvptoq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtkcqixbvk.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtzcdlvwre.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gttajcoieq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtdkibrejz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gtvszpvlqb.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcsjldjv.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtsmuoeytj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtlhljgeyw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtlentzvoi.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtezicynlc.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtlciueqfx.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtlhnjsbzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtzonejrzz.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gteceazmrt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtmwxyzfyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtjqstwqzh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtjxjpojbe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtojqajung.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthbfwebla.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtelhikjuy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gttuljjjia.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtceiefefv.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtdzzlooyi.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtksdsromx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtuycimylu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyntimaz.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtmglgwggy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtefxznohx.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtplpggzmr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gttxzuowgc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtotdutgwf.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtuezhlvok.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtnflvyzoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtehrdhbre.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtqxwyonxk.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxfjenqd.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtyalgrien.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gteoolyijl.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzcwjhtd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtylziyhrg.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtycowllhu.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gtvyrgovfs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanhrcppi.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtvlgatsut.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirjhrqrg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtloiswaqk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtvjhrxryw.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtphddwlls.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gthyjoktnq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtbacjmxgo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtrmfmjfxw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtvckeszkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtymbuqzow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtvqkpczbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtvuueygwo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtvhnqasos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gteyfbuyzw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxrofgnu.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gttwnycdpb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtftubzeas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtkazfglbh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtplcexchd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtbjruymwz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtfimqliik.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtbdommukd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqppezql.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtxeygyqef.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtuxguzzge.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtbzmufmii.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtjtpwcjro.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtkutmzeip.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtcizwaitj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtngmkhkfh.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtfhgpmyyn.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtetgwgvlv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtqyvuwptt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtsbpzhbjm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtawcsjouk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gtwxhdndrz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtfaihyrmg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtqvqusjey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtkxwbgsdl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtvgelvbaz.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtzvldidyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gttybzrwbx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtrekdsmks.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtqpusmdpk.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gttitfbjda.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtvxmburoe.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gthhefukid.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtaeayhjvp.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtqbbbspvh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtwftrnugj.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtpadqmvci.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gttauyfzeg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuzcmrhm.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtjbjuunoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtsrofrmic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtyinkeymi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzznugaoz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtjqxeaulj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtefszrmtx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtfwflnbgj.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gtbpfpirlp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gteviixvgw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtjkyrtcwq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtlycquxpg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtfzvihvza.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtonykxclg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtqapfkyzf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gttppirojp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtkjeoxkph.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuopsewqc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiyxtrbg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthaujhuvf.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtiuwyaqaq.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtsouftcls.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtzfihvfvc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtvxdqqsuz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtfylfpvxt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtzcqclzbv.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxaoqvka.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtaknzglbr.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gttjyzpwlr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinjjbfql.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwvvdizf.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtmgqltslg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtbiirjhhl.html

);
来源：http://dali.dashuyun.cn/Article/details/gtnrzwqujb.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtsqeqryhm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtbbbiipyv.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtswriavov.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtglnalycn.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtsrogisro.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtkpyqbfgy.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtpynhewed.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtdszasusr.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtcbjqqssb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtlbdeyjer.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtarxqbefl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtkuwuatqy.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtsijvxaqf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtjwaqbkxe.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbspogcmc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtmdknozrz.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtvahokbra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtvkcpgxtd.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtbdrictlc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtskdzrsnw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtqjrfmvca.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtoapciodu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtrkyubucq.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtmztqdutj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtnpijurjg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtplchgwuj.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtjcjvwbws.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfzljxkps.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtlyxfuemt.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjwriggux.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtdeklvsgi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtnhqfcmcw.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtvqaayjzo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gtgcyhxgwe.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtafkbrjwi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtpdkumrbq.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtlnycslzm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbjckdnl.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gthxiyeozd.html


<!-- 参考信息 -->