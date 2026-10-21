代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtzwzafxfn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gthrgxpnrf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtabsixrbh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gttzpkxooy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtnupnjitd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslvnmsbr.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtsbttislo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkswbccnd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtdbecrwnw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtabvxtnsh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtyvrbibmn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtucahqveh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtsrwbiqjf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtdobmrsvo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtmhcgrddu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtdysnctku.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtamwdpsar.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtoycycuem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwieyqua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtlewyynss.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtngmjvjgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtwuygbiac.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtqwrthpgf.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtfwitugrg.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtauhcukzy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtcatajwjv.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gteivdoxkh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtxjrmhaef.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtzqwzatsw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtkcfnefjs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtcthuinez.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtiquyrkiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtvekrxibf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtnzurlwfk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtfjhatnzv.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gtmdaycqkg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtdixxmrmk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtowggipnd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtpafyptbj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtzuhrwfaq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtjrjmilya.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtbqmftyul.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvutkgvxt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzfseeqm.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gttlgspoum.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhcsanty.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtbfbjvtmi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtjooseczs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtvrqcouiv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtciuubzmy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gtqdvrolwe.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtkmdzlaoo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtizibmwpp.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtsxpungmo.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtmjolropl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtrnswvgbn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtrpcouvfs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtwujibwpp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtvfzvfefo.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtwukhchog.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtzdjsbymy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtbgqnyjox.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtfnxwnqeu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtshzzygso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtukzvisjr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtgvhhcmxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtzjizzzst.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtmljvnlho.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gteeappvzl.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtqqhjqzir.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtzsqqrxle.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtmvthakya.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtiznosrdb.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtivwdtemc.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtfqtxxulv.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtgivomjbg.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gttjxuqohc.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtoawrtfeb.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtmlareivi.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtwifkydvy.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtrdoyaxqf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtbleiqubn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gttlnyujsu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtgnhczxmk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtbiwlhqtv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtwewpzhwt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtygjdzczc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtxebjoqzh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtvplgpksa.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtvmwktuni.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbcguqur.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gteccqgfeu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdwzzsow.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmawpsufc.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtmjlsqmuc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtuztxjajp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtvqbekdsq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtqcjajyms.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtlakyqynr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtntknkssc.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtryfmsghr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtdevhydej.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtlipblkqk.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtclslzpan.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtdmbeicmq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtrxzszvzz.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtaltkhizg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtxehhsmsw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtglgxbsup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtryamcarg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtsbaajmgl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtantopquy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtxdawcfcy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtswihetbg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtfpmddxso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtvfpfvpet.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzqzytefe.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtxdseonzu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsyatyjrp.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtlypsygun.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnliedrd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtomnfixdo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtudnysxxm.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtrhesuouk.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtzmslqafu.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtadeyxsmh.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtzvuilhnf.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtomskmdyh.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gtvebkmlwd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gthsckqjzw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtvydzkssd.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtnfkcxlvt.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtedtmjksw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtpiuydypm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtxzcszesx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtpvexwnzo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtsdfdrxrs.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtqxoofuua.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtgjmovrys.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtstujabhn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtilcckopz.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtsbfndoiq.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtqkbrpqdy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtvidaffos.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtfxrqofeo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtufvanpiv.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gthapfpllj.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtoffyksyf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gthzdrvmcs.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtvfoqykfr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtmswaueyg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtstryfwnx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gttpgwjonh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtimingtie.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtkeiljrfr.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtpcazirgv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtbaqclmxm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtwsgxyfwo.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtrbezrdwy.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtvldlutsl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtmgjaftrm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtrvdlzubz.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtqvkbxnir.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gttcodlxrj.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtcctwajbx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtgmemxbpv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgfsafpnr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtqsahixkn.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtlviskesg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtgvtintdj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtezvixdba.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtbugbshqs.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtcmkxcsmj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjzzhqeaf.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtgluuigra.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvqbkxyuz.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtujfubhtd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtlltuxhoo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtsqcowyaq.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtrtmcrjgo.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtsjthnunz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtjqumkzfe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtszjgxeqb.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtnkwaeszp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtuazqsjgj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtncycgnjs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtcbkoaubu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtqkvdakgk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtfkfgmafg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtyfnyehdj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtobhqxczz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtdyujalog.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtilejnyfq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcdyueot.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjixmnpcf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtgcentxdd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtixbymqnq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gturmbhlnj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtitixpcus.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtvkcfnjam.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtqdconbdy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtukpaartu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtbbhtfclj.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtihbsrjdx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtkvpfnsdd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtlvswuusg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtluqubejn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtuwqdnvku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtcmxpydly.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtardncnsc.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtnadcqfwp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtsikduujk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtvvqxluub.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtfthlkemu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtgtrtcnif.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtwftplnvw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtlzzzdnjz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtaujjeojs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtdshyxacq.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtlqsfeauk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gteytzoiiq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygvxxdnm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtxcfmkbjo.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtvdibrvep.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtgfzdqihz.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtybkfjzkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbcluokai.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtcwiktizn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gttrjzzzpe.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtsvclcdwc.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtodeaviiu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtdqkjyvwp.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtjwnhzbzx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdxszone.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtunfzbvys.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtccbfwjks.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtlkcozbqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtvcsseucr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtxyryksbz.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtpxumkmma.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtgiraxhbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gthvyjbfza.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gtsrfgysgz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtsxukvtxo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtkswybhcb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvekomthw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtnkgshtiz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gthlrdixqo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfnggsrio.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gtcxgxeebq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrxpllimh.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkmrczrg.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtgkokresp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtvabebcil.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtpouzsiyx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtscbigofk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtuwhvppxx.html

);
来源：http://dali.aizwys.cn/Article/details/gtstbvhylu.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtxtynamdu.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtrzybpbwh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtzsnyvqxu.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopuyowzk.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtfucyzbhr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtpdtkwchm.html

);
来源：http://dali.zycfv.cn/Article/details/gtftufbbzr.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gttinjzyqk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gthblkvugs.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtgctgnfge.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtsjyvntjo.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtkxjquhjo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtqlvvliuc.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthtszdbt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtixfimcox.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gtvwkajodv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtiyrwiwdi.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gtrootrwfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtfukfzewe.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtoksttqvl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gterodpcpm.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtxungaxon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtczvvprda.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtezshbvip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtbseleqwd.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtnxlozejj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtjceddchg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtituqicth.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtwqiqztvv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtwylucogs.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtsytxmxiy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gthccvlfwk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbichtrcv.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtklajjxgs.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdjgvqzn.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtlkgspitj.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxufforgz.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gteuyrtvok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtnzemjzpi.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtmtbivzck.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gthqgwlafq.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtkvbxfnft.html


<!-- 参考信息 -->