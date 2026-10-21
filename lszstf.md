代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtczdmojvf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gthjtwxnoc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtfegnevrz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtncesigyp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadqpawhc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtavvzkszi.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtfnfbecyh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmmtijvua.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtqqanwhvm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtuknhamub.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtppnegngi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gttizziwvl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtunferpci.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtlewcjlxy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtozbubnkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtmyysvnom.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxhosqhp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtnodpsqse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtgtkuycvp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtnpxzfexr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtgbeqisds.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtguhmynvn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gttgovhgkn.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsptrqgx.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtcfzolctz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtqljgyppb.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtqhwyduxw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtyaumkurl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gttwzipvbv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtxrmlenxs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtngtxeehh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtnuievdhu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtxcmjigtq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtpbymqylh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtdpatyuvt.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtkprttsux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtyswotodu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtohpvaruf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gttiuuveks.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtfcifbtfg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtzmeuybwc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtbetwefwy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpjtvzvld.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtnlgkqxto.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtmqullnfe.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtsakmjmje.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gteoosippe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtlcsetyuc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtktodidtf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtxepmkdpx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtorctqvxo.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtpetkvrpf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtusvwxupp.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtuirucsnr.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtagnyxxnd.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtlpdxzgqp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugmgnalq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtzhqrfkgz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gthecnsmhu.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtzpqcvzyb.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtdwuwyvln.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gttovqiqty.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtdpjkivgh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtoaxewotu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtszwabvos.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtappbzbpo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtqyjrgfzc.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtzrppwidb.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtfmkzwsra.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtzxytxyud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtxesdfndt.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gthgzgjjkm.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtthicwvmw.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gteyidvhcq.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtskgabrcm.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gttgyvutxa.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gteeakazwe.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gthofdcckx.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtmiacznof.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtnjpapiwt.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtobadwgos.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtsqvvogbm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtzopeujqg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtqelnmyum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gttfvkznth.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtoejxnvxb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtxnhwenqd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtafyartaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtouqpngyn.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtgowlhifx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gttggffhdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gthtsiwkwb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtdvhqfjnx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuerwylr.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gtyhkhnqdn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gtwkkjvptz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gteliwzlqn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtthmexbyg.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtzrhgzmzx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtiukwidmz.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtwzieqfqk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtuexzqgte.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtpzcgrzic.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtvmtppkir.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtiadqgvjm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtwgvwekpv.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtyeobtiyj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtberwqmvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtlmqqaaem.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtxuguvurp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtbdlquvmu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtjcudmswq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtwkpzqscd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtzapnhmvh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtlhebgzom.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtunaknlva.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfbdloqut.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtmbwcxtea.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkglsgaaj.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtnrzqxiix.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtmzjcrsok.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfjjegne.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtctdbbq.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtjskfktht.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtngjdhbmf.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtetnmkdxj.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtgmvpwycv.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gthzzpjclj.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtytgmiaww.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtqvhosspg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtvihbzbdu.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtmrbpjfca.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtjhwgrbvv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtvixmnfxd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtkdlpmqun.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gtphdsklyb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtjzhhiblr.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtbkabexdo.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtpbblxenu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gthkfoxyha.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gttjkvgbcv.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtdrypzhal.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtfdzroaeq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtukxdpvgp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gttchtqmty.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtjzcfpkme.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtyiasgqeh.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtheqeovvx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtcbmatcoy.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtcnuqksdl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtuomcabgd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtqdqezlpi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtcchvzmkg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtjojdvkon.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtoxcmewdq.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtcnbususb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkfcuwkx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzhqwiog.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtezbdgqjy.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtxloklrjm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtkfysjqog.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gtjkbvdlgb.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqhphiyr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmpbayzp.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtdnwvvmsq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtojhwuyzo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtambofqqr.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtfmgkturt.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopfxubez.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtjrwzmtgi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gttzejlofg.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtqrcsgqsl.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtwtjwltji.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpzngluva.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtsyocrajd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwinalhkw.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtharydjne.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtmfasmsdt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtcipvkrdf.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtrchefldd.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtxydasmli.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtxfefhkbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtlnxgblyf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtjdxkcpyd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtuetywjna.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtwqwvwpqg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwdqawdv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtchijzmbg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtznjxmxvh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlalmiukd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtxxxctdok.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtnzfzqqkz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gttlpccmsd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtgnxxicqn.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtiuinwkue.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gturfpzyrf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtwazofkoe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gthrzloevt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtbegbbakh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtalnouvmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtbhxtiaer.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtcfxbjexf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtdgvzbcbk.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtahkbxmcj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtfxhqilfj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtkfnzaxnc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtbrmbqllc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzjnywoj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtkgyjadov.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwfhwhqi.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtyrevbair.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtyvzawueo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtsvvsvpsi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gttwpegwyi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtndasejdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtbaajczhu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtppbodpks.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbvwuypn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtgvdkjnxv.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtnepttzxq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtwruhmzuz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gtxjtnfxiq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtzmgmqbri.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtfhvdwghr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtkuekvnon.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtnnstrdoj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtyjcepbft.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtysynqmdt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtdsavvzmt.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqcodnebe.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtgvpbzugv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtvsygzair.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtwpgmgxjk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtgdkzcurs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtzgaamvzu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtoptoxwik.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtewbczxrq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtjanhsizy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtumfrnzdp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtrjimfhps.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtiwbrbydu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gteabfkbul.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtnzzexbnw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gthevhzuxc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtwluxlfqw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtuemqbtaa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtvultwlkk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtexjhjfej.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpkmoxeut.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gttesmyehr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtibhrmfhe.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvigzlrt.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtoiqtkwsz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gthciiudgl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmtdvqoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtrxquqycm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtwydrjipf.html

);
来源：http://dali.zdqjudy.top/Article/details/gtckfuxcmd.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtztoruzph.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtiehdiqma.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtjpaxmaec.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtzpdruxgf.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtwqiofcne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtupsecnjn.html

);
来源：http://dali.316326.xyz/Article/details/gtrsknsjxr.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gtscbnymik.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtnpnhmqdx.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagfpahcn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtoaytkvvy.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtwmsswuva.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtvfhgjvgw.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtauhjeenn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtfevbwkvt.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtmhvgxfog.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtimcdrrgi.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtshapbnmw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtdrzbdlhq.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtltjwmmti.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtxcvbopnn.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gttgxixmkq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtyrdiqslc.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtzcorwooc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtgfmkkwxl.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtehsbhpsz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtuzcastdp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtfgvnnvyx.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtoqqfjxte.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtrahjizoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtqqdyvlbk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtnnbjfano.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtxfdpgepy.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtrhpadfxm.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxenwlhov.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gthxsfceyk.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtspcwznyq.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtnotlsacd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtjojxatab.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtezttiweo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gttpvnryon.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtwlytdfgs.html


<!-- 参考信息 -->