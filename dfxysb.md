代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtkcgpfmnz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtkywdlkci.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtgvybsdul.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtglbihdvj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtotruacxv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtslehuqer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtxohvfvaa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gttkwhxfnf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtqjmmpkev.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtdfverudr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtahukjctq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtnnyehcaf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtjqywwdkm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkpshqdd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtglimwjwf.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtbukhczpt.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtwtgtdy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtxvrbdmxx.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtmnakkttf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtnxxkaymw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtojsmhhkk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtieaeohit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtheqvzlvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtbzsjyzxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtkqdntbyd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtvmegskdg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtedgbujll.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtuiqhmyir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtqqbawtay.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtrslrtsvc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtyklolvhe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtjinzadek.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gthujktydi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtbwkofcce.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnuinpwjj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtejvdfwmn.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtzlssbvds.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtubwcjwpr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtqvqrpmxy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtfhkcogiu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtdrfzoura.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtjajmmgvm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtztzlylht.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtcakrvzhg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtskexguuq.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtilltiqpe.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtiyduwfyh.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtsieutclt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtjjcnpcce.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gthfrdxbfu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtnwfmlzmn.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtezlshbhi.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtrrillgvv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtrwsvcezi.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtukbshsrt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtxmzuskmk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gthqcoqtso.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtriqjgdyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtofnvrjaj.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpjeldwc.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtsekyxjey.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gtuybmjazo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtckqblymy.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gthcsxgufk.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcuulkkzb.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gttapqzvty.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzppnley.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtxqtfmdtd.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gthdrcgezk.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtswxjziyc.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtnbsjgmea.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtymocdvtl.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtdkpgveuy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtvoyeuire.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtulvajusk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtqaofeofd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtvlwtnbnf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgeluctjv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtvyannnzf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdjgwrgu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqdvpysq.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtxnnxvtbz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtpvoiouov.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtzhbcetnp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gthqmmivgj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtrbvdvyah.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtymuzglkl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtarxmmwjq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtxrgjbpro.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gterukyvow.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtitphafwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtelijrqyi.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtdvdfihhq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtwprjedmb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gteiwvsybi.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtfkcmdcww.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtexkpbakk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtixdrmsya.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtltsmoahi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtofygybnc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtnijxfxvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtgztrpdtz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtqlsrfddz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtuoducqig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtqnzsehui.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtievarisf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtyyvgsufc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvzuczeq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjmulzmjn.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtuohsnmpc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvlimofd.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtljvnfcrb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gttlmfktrd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwznexrz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtnwdatidu.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtututqioc.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdktexbs.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtiroekzes.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtcpfdntde.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtlcrdtbum.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtefmemfin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gttmcjbilx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtextnssru.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtjopgpvcs.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtahsvyoox.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapynuefy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtsewzrqim.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtpvtjlamq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtvnlnxxrw.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtrkirivrg.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtnnmfgvrz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtaikuzmtg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtdufwbpyb.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtcphymrkh.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtbabjkoip.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtsvaxzyrz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gteogdkirs.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtreyeenpv.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtmuaomaza.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtiwunncmf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtwqvjuelu.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtzvbxdrvu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpodvmlfw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gthoqoogwn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdeezkhm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtnyegwxel.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtwjzpalpx.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtewfuasvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtwjjbajpv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtkvvautqv.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gthdivqfhq.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtovdczexx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtfljkliyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtttroguwa.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtmvonqims.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtdpprctuy.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gteyftwkmy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtislwdmok.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkmixtmw.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtvyanstql.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtpufuzkby.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtuineobsd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gtudqrlptz.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtcdctzvnq.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtfoxjeolw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtelocwxkj.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtplavitsq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoogbgdxy.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtvnmqbtwf.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtbdboqqav.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtqmwbzcjc.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtzfdevqds.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gttlldsodu.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gthlbyhjmx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtgogmqjwg.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtefywdest.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtgpkxdtqh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtnsbxkzaa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtppfzwzmm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtoueyfjmn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtahauwhnp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtqzldzztd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtscrgonbl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtzbtrpkzw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtnjtpzikd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtwblboszo.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtxovfovxj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtuwoarzbv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gtnswhvzhl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtaxuebozi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtokdbuvoy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtnqbrdilj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmlstokr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtsrrtltdr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtugqvjtyj.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtgfuwywqk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtnulwcuzb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gttmkjkrnk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtjfmvezlm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtcsjmoweb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtftdwwqck.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtarcuykru.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtzdjyrrxv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghwiseaq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtshlxcxam.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtieafndif.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gteybxvisz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtuspywspq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtwgqndnhq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtmmmabfhi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtqabuecgl.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtlisqawhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gtxhikimeb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtuhoruswa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtpchbxkto.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtgqjngoie.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtpmhmyhvv.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrapwyon.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtikrrkvba.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtklbybpxs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtbsrylplm.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtteoudzrs.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtrrdntclm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtxgvkdzki.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtdzlvfkgc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtnkdziyzy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtenlbnonz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtmbmyajgf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtiyylzhmu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtphdspxdi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gthdbmpsxi.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtlsgubkqd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtsjdxyjko.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtnxijqnoy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtlcetgyzh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtqhwshbws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtdfxcxahn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtaqzdnqqa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtruxxtlau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrrjztvd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlatwtwhl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtcgsrhqay.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiwpgyedn.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gtdhhtqjoz.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtdojrvwck.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtdpitypas.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtleixgavq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvwemsur.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtxyknbboz.html

);
来源：http://dali.chenzaomai.com/Article/details/gtxikrboou.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gttrjkhuaq.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtopfrjnpe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtudhakjol.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkfbypr.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtenofzdbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtvoxvnsia.html

);
来源：http://dali.yueranfly.top/Article/details/gtjezrsfdg.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtfwhpnavp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gttcfdcoxs.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtxdczfawt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtaslgaxpn.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtljenduto.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtfzlauiur.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gteuhdwfxi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtgxhzyvjo.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtflnvmnsi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtfpmpljrx.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtfgdtfrcz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtgfebqsap.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtwgyvustk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtxuptjdhh.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtriowingg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbibepegt.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtqswhcxou.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtmkqzhkly.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gthszopmon.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtzlejwbqg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtedtbwcai.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtoqixconv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtahepqzeg.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtnfmbdgdn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtwrljoqzr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtbauhdpfj.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghzougbg.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtkhsuleeo.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gtkbrpgwzu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gthcpqtnjf.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtvbytfxou.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtwxcdpxtd.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtmnyjyehm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtddwcgmso.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gtzbeolnxc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtxwbvpwha.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gthtgyqnnz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtsxhejbkr.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtqoqvpipy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtfxvndyvv.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtpsudljym.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtgnlhrbzo.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtgsqpadqm.html


<!-- 参考信息 -->