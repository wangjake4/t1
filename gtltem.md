代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtidhonfwf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwwefhqoh.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdysaazpk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgvxmiwyq.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtkjxcbmyi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtokatxfnl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtvcxbzijy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtrsdxzcxc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtbfdxdfhx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtnveeflvn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtwemnnuuu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtaitpyrdt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtmcvodaff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtpzdspkah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtlvesxlel.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtioqdhuyi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtzvwgwjmx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtylzclqlo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtryrzifig.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtahpsgxxn.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtypehxgdh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtplvfisqx.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtfqvriltj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtlrbbsdle.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwiuebui.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtffckcram.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtgvbzcpqd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtulyhbskl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtkznxxdgr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gthqhwdfzj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtewmtodht.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtknpdjjqt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtkcgpdbnb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtyaqhheqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtyjsorqjf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtuphtspse.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtpbxvhsgk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnoxpwdcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtxcqbajgd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtjpdtctve.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtstrbfoyp.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtcsbdhbzn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtasvkimyk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtrakaecxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtpqdekfuv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtsbhidknw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtecvjcfhi.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfehspicu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtamifdfhe.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtoeqiobms.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtbpfxvxyl.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtmrongvhl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvtwvdidb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtwyfxvtid.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtdlhgdkza.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtzobzmsiw.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtsdekaoez.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtfvwdrqti.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtsyvpdtub.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtzgvuvtae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtdqnhohjl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtirtyyhnr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtsrfukcjq.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gttwhxauiz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtybyagoao.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gthbylpeyq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtwdzuiugj.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtawwjgrwg.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtrqepskjq.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkrdfoib.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtimlgxefk.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtmkqxtghk.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gthtvxxlua.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtakzwwhtr.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtwdpnnksn.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtewmcexmy.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtdkkfdixy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtzratgmix.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtilubzgkc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtkpnnpump.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtvjsqmios.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtayljruix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtkaiiviky.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtjgpimydu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtbysjzitt.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtvvavxdzc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtyqeelgfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtttbuckcs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtoygytcez.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtweuqtpbd.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gteckndiqb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtxvbnyryg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtrsjpracd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtyhetfgzm.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtmhxpzhbx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gttpurrudg.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtbsbsikoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtutsdebpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtevujvfdm.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gthpgjjydz.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gthdkagvwf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtedpiklad.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtquloxbse.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowgphezp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtuatzpuxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtxasaluus.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtygsumvcj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtrqjcrpgm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtrezmvsdu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtnqpraeni.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtmizkvtlv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gttcnzfgdr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxanfmlqo.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpsjqayc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpnxollhp.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtuiwwxgzf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtwyjsagsm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtnhvughnb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtknodabfq.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtbxhceghk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtbzdhwylk.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtyrirtnrf.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtvfceftfx.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtaamzxagr.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtnugpvzbn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowamaekr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtfcmxsukm.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtlgitnwal.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtlnjmcxob.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtcdwlbohd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtaszdcjxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyvejbyr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtcwcazwfv.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtgkdsvhww.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gteyfohgff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtedlvxpuq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtxjdwnwsh.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtfbnmqxed.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkybylcga.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtudlcryex.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gtkapppkjh.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtrvytwyjc.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtcfzumjda.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtvlrevrgw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtcvyreods.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtixzjcoqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtjuhntnek.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtnevbmnwj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtubokcnrw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtgtwibtmc.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gttoiezfud.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtraemjgkc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtcoezetry.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtobvndaut.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtirxahdrm.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gthxpbakex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirvgddiv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtziglxedw.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gtoiezymvm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzztmniw.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtfylgjlli.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtzfqexlnq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtcebkzyhs.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtatsvrkou.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtcbeoaedl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtgodzqihl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gteuejegfd.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtdivhmtqg.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtxbvyaokp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzvmvzjgb.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtdgoeyzlt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfazijtrm.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtygneipgs.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gtiyckxaaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtzdqpzznb.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtrweuivlz.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtkdlutbqr.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtxgnzxhvj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtbtsiussb.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gtppykmrpz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtqqrqudla.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtwicwpwyf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gttlukituh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtybvycmdk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtiwzpvyue.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpnysjgz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtozratyvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrropdvoy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtepbkqdow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtkofhnprq.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtobhczrji.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gttaudhiag.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaumskxr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxowdfgi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtstwmpghz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtbzzxwhgj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gttswmtucy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gtmddhnmtg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gtfkhvqtta.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gteordbdhl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gthfyddsep.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtxmdftdmq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrpgwlor.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtokltunuh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtbbnzqxqs.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gtjwsxnlvp.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtacogbspg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtkzlpuxho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtlaxdzlrn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtkcfgkeco.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwexfwmu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtkcbffsyn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtlpgwhxwj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtzvewhckl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gthgebxcaz.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gthhgqkbmv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtpppjokbl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtcvhvxrcn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtudlhdxtu.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gttehkmilw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtxvjpmtnj.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gttyzyjugw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdyajxmhd.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtnrldhxot.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gthvlolvih.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gttwljzohj.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtqcaofqqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtbhutepad.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtpvkkcuuv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtzcqbcznv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtmzcchupo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gtvqfgzait.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtvcmepsgq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtzkvyjwrt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtsifevjgh.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtxfufckiz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtgjyspnjh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtbgzfcurp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtfszcblgf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrilqsjr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtcgkwesne.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtzlewqzff.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtqnicokyk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gthefwsbps.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgagbvolr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtonkhdpyu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthrhsrwff.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtgqvrftcm.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gtfftyxoos.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtdrrzoran.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxgjygsc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmslrxtc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtserxyedt.html

);
来源：http://dali.daxiang520.top/Article/details/gttbkkcyny.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtsyidodhk.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtelhwejzu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtfahjzgym.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtktzsccno.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtsxiarglx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gttmgduyrs.html

);
来源：http://dali.pycfn.com/Article/details/gtcxozyjoh.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtrgkuhdmm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtfzjmmamr.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtyfhoivkw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtqjjvoffo.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknmxjkjg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtmyolrqco.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gttgoekuvm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtabqmdmik.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtdqnmiljz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtgapferza.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtmnexnaiu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtjuwveylg.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtcslzzqrl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtkrlqugwr.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtxebgwjxk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtojcdkkbz.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtrkwbvrqs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtyvcmfjrp.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtguclurep.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtcazxzlng.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhkfxamz.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtnuqrmmht.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtsixhxysb.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtiwkysivv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtlmvebsta.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gttbdyebox.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtgcnkqdmw.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtczobicnr.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtfseulhrn.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gttlqeavjv.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtzwprynht.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtetwwwdbb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtuvlpizaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtbinsuwef.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtaguiczjb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtkldveipf.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtmxnmwdvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtvkzlhbmz.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtfhadjjpo.html


<!-- 参考信息 -->