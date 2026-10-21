代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtxedzejam.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxqzdiqpb.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gttmdhgxln.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrmakmsxc.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtwnmbmjve.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtcpmclgad.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtdkqfbqds.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtpxlhsnmn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gteexwifst.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtocrfpoxw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkwpymcwe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtryqhawik.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtgiyavioi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtsltyphcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtucqiofbh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gthwgjkiwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtywpwspfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtluxjvuof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtecfmofdj.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtljzvlxzj.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtkexhdlvm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtqoiaxrir.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtqxrllysw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtywvszfab.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtvpamorfj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtastrmcec.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtcjghyjbs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtibxhivbo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtobjnkend.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtriyubsyi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtujivmbrz.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtttndjctj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtxszshegx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtreukgzql.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtvcoezpaz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtkdvkzllq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtburyeqqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtwrquipnx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtugzclhzf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtqdfsbscf.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtjmustioe.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtmgiwmdmn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtjtbrbnxl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtqdbqklhw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxwsuspz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtxgngajky.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtzxoizfgy.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtvvsgubeg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtrveqltxl.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtfjqrgttk.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtkkpivger.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtwejqgpzu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtqjiaimoi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtsauubeqa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtnboajjgk.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtzocodshl.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtxiyblkwa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtlhlpahfu.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtpgvwsvfg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtxywsumpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtmiofyedt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtbcdimxlp.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtgtmnmwoy.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtcnztzyxi.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtcssojsmf.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtqvodpixy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtpgniqluu.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtkcmzcnpo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkvujvkxj.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtfnftrmmp.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtnhdfrqxf.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtujdnbbjt.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtfyflpjwv.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtxaomgknb.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gttialpcsf.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtpbjiwapc.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtodpbxtos.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtglnblghf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gttqiizncd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtysbrvwfe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvooudntn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gttwzwxwgf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtfsaamarz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtsgedaqqv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtqvfavoal.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtbryqjhuz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtniicitwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbvuggiqa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gtzqcakprk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtnlrbafcd.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtqmcfmeda.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtrvdgalqd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtowwfoxtv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtbaypcmsz.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtjkkeyuhz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gttsqvgeyp.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtrailjlvm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtahtfqdko.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtopspungc.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtquuthbtc.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtblptxyvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtmfwnxbfq.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtbsmztdib.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtlbilwoug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtahgwkylx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtbsdxaqih.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtqmbyhtay.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtyzzodepo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtpxdknurb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtlrxvarbk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtacjcpyyx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtuktyahzg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoidfylbw.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtkqzclias.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtiavkvcql.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtnheeqrfw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtqlwycevq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtqteegpaa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtsbwdxpmp.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtamkrwoju.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtzegrejqj.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtlxqghmxq.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtifncwdqj.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtbiqycteb.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gtiulfzdtu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtgofglepy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtaapyigbf.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtkykxgqjv.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtggigepeu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtorvzqcyr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtsvrzblqy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtftequspy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtfbiapsok.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtemckkzeb.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtqhpcccfc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gtkuhekbwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtxgabnpyk.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtxkekfzbh.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtcsafqcuv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtsfukqnnc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtvhysopzh.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtvkpimipa.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtlxxcrhvs.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtoymepapd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gttkmdmemd.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gthbhgclzb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtffahtugc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtktktefto.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtuiabytyj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gtrfsywvks.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdbmeredd.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtdjsgpibx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gthlyvvcmy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtqchooyno.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtloanjlpk.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtzmcnfnii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtkixkjvts.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtevufpbsj.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfewbamcx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtbazryaqo.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtdbandjbv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gthuokeikt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtzjoyylgh.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtfrrmykso.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtsxtinglt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gttckdnavl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtdgiobews.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtpsuuyvsh.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtcjvgztqq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgwqnswfa.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtrkbyxpgm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtczoakudj.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtgedzrwhu.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtyvumvaio.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtljoqxgrm.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtdealhlzo.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtvvjdillc.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtxiohxgzo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtkzovgozo.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtstzsfpny.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtrcpupxdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gthwllubov.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gthgenknng.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtktudhxug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtoumvonsf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtmceduwfj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtqpezkvlw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtyepdrgiw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtveqdysxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtvpxyfxqr.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtayxbqbua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtvbkdowax.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtumtbzobf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqrcbgme.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtmwdkdytl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtghvrkeja.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gteswmeuao.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtmtrubqil.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtkrmllgzx.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtxiazfliq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtqthupnvz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtiyyodkha.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtwwatzxca.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gttpzkyatf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtettlaqib.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgayyxyy.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtybgpgylo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtfhlnpyff.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gtlkkvsrxx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcadjaen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtguqimeqp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtqnxiaomh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtgdkwsrcb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtzjacqfck.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbzoavve.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtpdfzpkyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtoeojwhem.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gtobloblyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtcjfbbdmh.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtlwzicbjg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gthxsqirji.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtfvvkdsvv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvycahwwy.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gtzhmrkaww.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gttccbabel.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtlnovzunn.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gttaejtmhd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtjjafwnza.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gttzcwfgve.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtkixrewjo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtngfkwipp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtmcauzsjz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtdwmmfsei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtokdwbfmu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gtrjostpem.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtllfnighn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtawjbkszs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtwreyhpap.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtqhaefuct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtupukcfir.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtqhehkzbo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtuzbljoss.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtsmxzfwic.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtopsbkkao.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkrzyxkqf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.havefunace.top/Article/details/gturkfmdva.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrjhlnsc.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtsaoiycvj.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtyasrtibc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtiwkxbyxj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtnyednqcq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtdgpqvsxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtixcoywha.html

);
来源：http://dali.andypj.xyz/Article/details/gtwmcjtbua.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtetqijmls.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtorrubtin.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtvwoftfqg.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtpaqtxrha.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtrjujxcig.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gtvphymmyi.html

);
来源：http://dali.cheryme.top/Article/details/gtbsiaegqb.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gtuicghbzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtwshhkept.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtfurfpvkn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtttiuuice.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gttklglccq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtuhtapiqr.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtcbmqdrtg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gticioqenc.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtksvmhmda.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gtmbeibpaj.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtfgrlbutw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtxdvemzgl.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtgenakauk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtzcxtnems.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtoubdvxcz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtvyspklto.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtuwuhqrxw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtnnelswxi.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gtsobvhona.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gttwjefjnj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqvugjkg.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtokjkzfym.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtdpfzxkju.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtfhklsqrl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtsbtdjqnx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtqxxwmrrs.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gtkylrucxi.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtztnrjcpy.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtsyjqzpll.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtbulvtnzl.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtudoluhmm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtjhoibjjg.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gttnlxjazj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtuujsvigp.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtanwdaqej.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtbbzkuilj.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtnlnvyizh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtnzeoxvaq.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtscxyrqlm.html


<!-- 参考信息 -->