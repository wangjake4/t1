代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtrbfdsyyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtdpfzbwim.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtnhggnlbc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtaobuukld.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtnhlpdnmj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtlhmgbeku.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtutkjornz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtesdfumwu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtyxxqnwzb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtioxkjnon.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtioucsidd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtxqxqocot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgnglamzy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtqpamzhsy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtccucwqkz.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwdgjmfjo.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtddkfbwud.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtreudyzms.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtynlmybsu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwcpwxp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqxurbyi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtxtqykyaj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtmkbhgeft.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjxylojf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtelkglcrk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtrtpmaboo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtaeitmkms.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtoyoypurt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtimyjzwcu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtfcxslpyt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtfmgeloyw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtaleqccrq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gthmssnapf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtgoqaxvtv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtvdvihgnm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtgjhxkbhw.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtfsnbyide.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtqfcwapth.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzizpwbeg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtbhppowou.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtzdlozfcw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtxlkbxksx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtfrbknerk.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtcqfusamc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtqarggejy.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtucxdeuiy.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtuvjnhugl.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtzmlykdrh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtctfgtwxj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtcyrwcloh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtsbpzntgd.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gtyefcbkcu.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtbinqperi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtdhowcglr.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtxqrgdzqt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtxkllyfrw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gtcvliwpoe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gterrlsutn.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtybtrdyyw.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtpojmxgst.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtonpqzzfu.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtgprdnljp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtsrycrnni.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtamhpyjst.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtaaovuhct.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gteuxtveeg.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtdsgzzvpx.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxivpphmu.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtvbjtjpgu.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gttomftdyd.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtosyyklrj.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtendkbpjk.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtutbbshco.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gttlknzojl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtyegxgvzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gteotfzidw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtzattvyxw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtwzvpttrd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gthpivkyuo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtmdnqqybd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjibbzjev.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtcbeugppv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtwrfphajv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtheepkhnw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtrptbmqfz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtrvcjebox.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtktjomsvb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtwjyqykfx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gttsoqymus.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtrdwproev.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtqxklpyof.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtudtpqbny.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtqskzgywc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtyqwecmve.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtyodzvquc.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtifemgniy.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtkxrztxdo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gthozqjayg.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtporamdfk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmlctawv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtngspdufx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtomtpboog.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtwpuhybti.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtcdrrhugz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtwcvdxtgr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtfxygrcfx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtsndslzvf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtfsbpwqaz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnqhmaipm.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtqwcgmbwj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdhkynhol.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtwzhccwma.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gthkbzlhkg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtssqjtovt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gthfjvrukv.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtabdokmmh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtnrynifrk.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtovmdzosa.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gthwbsdwhk.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtgbmkapql.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtrpinqhpt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gtvevbtkqy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthelocoyj.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtoicogovy.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtplnuamoh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtveyepipg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtlccncdbr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtkhdwtltz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtxjgzgmes.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtrptcwzhl.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtfdyjnzjv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtmefhefec.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtpiugebyr.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtenjquane.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtxymqjcvb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtagwcpuws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtudzltdqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgceuwfwk.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtvamuxgka.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtwwvzfihn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gttfpdxvuc.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtcfrfzmig.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtssxhngpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtbmtegjoq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtejjawabd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gttrfuvyvq.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtvadyhvpj.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtrrwlongw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtctgnqqsl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtpsdfydvg.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gttopemdkj.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtrhcpqfmd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtnkuvfvpf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtplhakacv.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtvplvwhaz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtdmbkgfra.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtoejmohkx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtcfyofnxj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtjxtffbhy.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtnkrdryok.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtdsnfgemx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtxjdyhqjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gthcbozsps.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtdgeivmbz.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtiyhapqle.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrzeucbew.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtslcwszms.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqmyjgaz.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtdmacdoqq.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtdelhgtyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtiaaswbjl.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtxakkykpe.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gttgogvkoy.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtaeputvqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtsnhyootd.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtjipkntxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtddlaiqip.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtdnainxtq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtenvrhzhd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvakjwgbt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtvumclpqy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtsasrkwsa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtxjllpcxo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtpfhiicgn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtyypievjy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gthtnowgre.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtoccpxhvj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtudorznpg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtwgsyweiy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtgieitshz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gturlomgel.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtigtywkqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtxoabjtvv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtlrwwlcxd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtjrjgfbme.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtajoonldt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtijzddbcn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtpzazghtq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtyibmlast.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtwtlpvign.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtbmlvbdtm.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtyasrrkar.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gthsxtvnwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtzeysevoc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtsbweivtt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtgemkqyig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtdylkgggv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtikpcdboh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtvysxqtmb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtzqhrhery.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gtyfxrksbb.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtrtijzbwf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtpqqqzgci.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtsarxioff.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtnsgztuxx.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtcsvhmknr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtqujxggui.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtditwmdkj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gttzygpart.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgxbybrzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtbfxubhed.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtrtppjhos.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiafacgjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtgtkryojm.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gthssygoem.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtzdlwwvat.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtpcyhjcqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtnuntnixf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtszuwbgmp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtmdaybxda.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtxtwengnt.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtojflutqg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtdxrarjtg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtyumqtypi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gttnlcihow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtsdhuzywl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtgksoqlcf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtvgphvays.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtrzaqfcub.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtpoqkunzv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzkwkbzs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtywqnmkqk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gteudjtrbp.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtsumpitch.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtayofchlg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtrhjwbjsb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtcrxmyurr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gtmryvdtdk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtcpujxlkm.html

);
来源：http://dali.9152youxi.cn/Article/details/gtitrqnecc.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtyadojtqi.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtcupprvky.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtlzwwlzel.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzfsonba.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtewxqxzbz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtqnsbdhpq.html

);
来源：http://dali.cdnleiting.top/Article/details/gtypeqwhdf.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtmchhnpin.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtatvpnnpn.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtgxnjeueh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtuanazqcs.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtvsdfcdbe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtkvhqwpog.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtnmeidwgz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnltivsw.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtcmpncnek.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtodvpvfao.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtaccsqxis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtcydzyfqo.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtrmvgiqcw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhfwflnx.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtdrdepaen.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gtjydwqpcm.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtaovgecxk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtkurxmdbf.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtddzrqlhg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtysakbhsg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtoasxzgxc.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gttfoycvrf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtjjxqyynj.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtmslfykve.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtasqnsfak.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gttfrjzsqy.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtcsioexaq.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtmevslpax.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtnswqhrke.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gtwnicurcr.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtllelozar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtdedtezmm.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtarkhrzce.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtstcuvilx.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtqmckyeqi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtjjtardpl.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gttvidsmqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gthcszjgeo.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtkdwlfbjo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtxmfmmdjf.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtpqebnjpp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtijqaetcs.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtglrlbmee.html


<!-- 参考信息 -->