代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2fffaytee.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2tyctpdeq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2cnieddwe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2xgkasick.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2udkjtdul.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2gvdoprfu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2sfhpmtka.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gt2srslzkxc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2xxovwzyf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2mekcmaco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgfxhkjt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2myzlkaxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2gfgqreki.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2gemdfdbm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2ewpmuaep.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fgugvzih.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2rsgrihhl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gt2tfybhmih.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gt2reokafgo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2wkikxkqi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehpdyalb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2fqnliuql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2pzzeokfw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2ddpimpur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwktjvxs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2ksxthclt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gt2swovhgih.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2tojvbbmp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2cjragfof.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjcnbbfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2teusvpdx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvpshpet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rpnjjpxj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gt2plciasng.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2dajfkydw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2lsagvmoy.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlicnjnj.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ybhvqqge.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2hknklylo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhvqrsho.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2ecuftsqq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2fdgjoxsa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2bdxmpbcu.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2khggecrj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gt2wsonjylx.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loelxzaw.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2govokrop.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2elkodjpi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnrpgjyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2libvecsg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gt2uvvgmqib.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2luaotjkw.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2ngzsaqqc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gt2ioqjibuv.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gt2ababnplf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gt2fasprwnr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gt2krxaimnc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvzxwbfe.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lixjgwja.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gt2lmihkbkf.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2ezqldqcf.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2gmartjuv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2paqupfde.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2aceuilxt.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2jbdikzwd.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2xblllumo.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxwjsizu.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2ooukpqma.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2uxbubffy.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2pgqbmfbg.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gt2zntqbaom.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2tesbvneb.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooushjgv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gt2bwywlbgw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2eadhnwqr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2fyjvtakz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gt2fedapytq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2oucldjva.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gt2fjrxxmol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2cvwpgzvp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gt2wqepvbou.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2jhxsugzr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2uofutenl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopmwump.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2yqrkkmcc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkdorhgj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzxiervo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2vsgvalaf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2vdjoajco.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gt2bgmpvysw.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2dijxfyfs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2zhembxpe.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gt2tisskhdm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2tmjezmul.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2bsqoexcd.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2fdoyzepf.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2scsgkfjb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skhqlbrf.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2vqadrvdp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2hlkmhlcf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2jlubpecr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gt2lbehcmfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2elucbbes.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2twmthuky.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2leyrepjl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2vfpvomnw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2vhucfngp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2eknldpvh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrscsanz.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gt2trpgatbv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivakkvgf.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gt2fjnhirmv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2jjmatmsx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2sfjpmfcr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzrhmzqx.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2ksnkmiae.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gt2xbrhdlth.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gt2jxiooxpr.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tywitzdp.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gt2ltcqkfpo.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gt2jndhhdtb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2llhhjhnz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gt2myjmjbaj.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2ehasekug.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqpknmic.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2nfkulxom.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gt2swtmqebp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2qrfkqaie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2lfzvybom.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlxozfjr.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2cgmnyylc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2ojebadpl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gt2tqlovxvh.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2vzbtlbgo.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2huicjrfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gt2xuxiknbx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2hqfbeaia.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcjaflxy.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gt2hiwburjv.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2ffofqxcf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2ypsrnktu.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2wvhqurfx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2xhjixagq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gt2xlukhgnh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2szqtkovv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2ztsftcwr.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gt2mhknudux.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2uflrjbrw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2jckycugf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2udogjxde.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2afpxerib.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2xulezvjh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eefbmett.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2mlyxwxeh.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgvhgjai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gt2gnpedyky.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2kildgpgu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2wwgidboj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gt2ggrtanmt.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2ukofuikd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2rprvcspr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2icxwegkq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gt2ffppcrpk.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2sdqmshsw.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gt2vbncdpoz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2tafeckks.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2svdjofjx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2iwxywxrt.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2jzbsgwkq.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gt2izwfiawp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2amnhoowj.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2zgjlthjv.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2qirxysia.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2xkpylbzm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2babqmgjs.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2crsbbynh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gt2kkmelbwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2eqpuiunq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2bndqsuqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2geyiltbf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gt2zowwsqia.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilzejbcr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2wdmlchey.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gt2gzpnlqnf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2esmuhwul.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2lmtmrxyk.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbpqzsqb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2xgsavrln.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gt2bycegkxh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2rqcwjtdb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2bzchfize.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2hemztwev.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2xzycbgod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2njgvgotr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brejrajj.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2uocsrvth.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2axbbnezl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlqqrdfc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2pobiterk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2jlhdavdc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2wvsgarms.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2ovkydgfx.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gt2bsksinvx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2crllwgpd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gt2gczlunjx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2qmxoqezp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gt2orsvmwjq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2jyzvtepl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2uezitjmf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gt2wslzmpfq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2cqnptjev.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gt2epbuipft.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2hyzpngkl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gt2ccfgqtam.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gt2zxnoeuao.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2kdptxvvq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2gasjkqqt.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2kuogyent.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2aaxaicin.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gt2jhtisirt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gt2kifftgea.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tlxlwmci.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gt2absscfil.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gt2fmerbvnj.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gt2ncqadvsw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2qkstxtpj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2ecnzomcg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gt2wawhxzla.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2xtznwpff.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2erjpmmuu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gt2dkndyayn.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gt2iaozmukp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2frbkzhzl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gt2mhodwsfr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2nluulgqr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2ostbedng.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lifpuagc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2ciwcywbb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2bwyedtxq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gt2vpnemyrf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2pbnthrru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gt2qobgnxzi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2aktmycus.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gt2pfubnbtp.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gt2rrzhsvek.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2jjehegkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2wrdfkqxs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2dgrclvfk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2onlndhgl.html

);
来源：http://dali.xylfe.cn/Article/details/gt2iqljepro.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2vugnwilt.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gt2wrrpcndf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2wfgvcpdo.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2iqnhlmwy.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gt2wsdapmqe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2wettzrep.html

);
来源：http://dali.wangdashe.top/Article/details/gt2wypnpemd.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nflhnera.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gt2garwevyi.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gt2lubchzpb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gt2uvgrchkx.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfskszyd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2txiiaokk.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gt2jiwxibht.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gt2fqiarxin.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2iixijyez.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gt2tlzezlml.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chgybvca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2gbcwaahf.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gt2sxepmqrb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2vicdimez.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2lesfmjbm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2urprbhka.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2mlidxzxu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2evfyxgsk.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gt2uibubdtr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2olyaaxom.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gt2nxnvxrez.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gt2etxvqyne.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2dsjogldm.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gt2xdyrlnpm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gt2epnlxjgm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2eywrgrxu.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2lqqbcabc.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ficscypm.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2qfwitrsq.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2paanynhc.html

[Q17] 条件查询
来源：http://dali.hnqzz.top/Article/details/gt2ipkvgcca.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2xumgduqb.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2ncfjytnf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmihvpmg.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gt2njesrqsc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2cqcovjqc.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2tavzhfob.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2sogcisop.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2prklmtud.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2fvkttxhg.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gt2gpgodvtk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2knwvjyjw.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gt2ofgkozpc.html


<!-- 参考信息 -->