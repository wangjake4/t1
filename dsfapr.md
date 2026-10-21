代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtexvysvfi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtwmvaceot.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtcudmsscc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtobfrnkyq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtqmbyvqjz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtosgxkphq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtjytfdzvj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtazykpsrr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtnpmkygxo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtflvsxeth.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtkdacfkiu.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtuddnqepu.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtlwwmqdjp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtaofsmyra.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtooavlxvs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtxyquegif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtlywkordw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtnnnopccq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtcbfdbpzo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gtdqzzskqy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtdpfxbitd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtdmjocsqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtzlxevvbv.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtlgovxvxj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvswekswg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtestzdixe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtpvlkqelv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtwkkwmqxc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzcoltxp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtwnnydqoe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtajbgyrsg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtfqlmxcwo.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtoetdfmth.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtjyeuyjyb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtszpttsuz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtboolvxed.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtyjvxdmky.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtyxndasyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtxojjwvfd.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtbasspgsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtixlhvong.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtpgoiwppl.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtfpfivbpr.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpezxuiz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtfmpaihem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvqruotbc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtslsbvoom.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtvpjrlsbe.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtfhrkazpf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtgojbdvpr.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtqknctqcv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtgtrbfiao.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtezlxnugi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpliywvho.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtecscqscb.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtmxzpcbbu.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtikcnkurr.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gticeakfri.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtxrdazazz.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtozzghqup.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfjegmvnt.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gthkgqcdct.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtbisbyvjx.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpgxcxql.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbddwfrih.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtebjymcnc.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtwykzeght.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjwrtclps.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtwwmxzalb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtlqfzocdr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gteodwohdh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtnhxkmblw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmessjhi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtodrrxqvt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtsrlfiyrm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtsmwjtqpx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtshfpcdrc.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtdraupxuw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtmahqkyci.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gttcudlzwo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gttsjsjcqc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtojxfrtkq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtjksvvxev.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtyzqifwbl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgifxemoy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtwszaaace.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtdtxhugeg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtekvstqpj.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gturppanju.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtzxysugce.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmnjimws.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gthzpgmvnn.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtmqbohufu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtiuozdqrj.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtpsejqbjv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gttpznnimd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gtnntroqnv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtvzuynsmm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtrgzesspx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtwsgtrrwc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtargughts.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtbarhdfnp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gteptlzzns.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtvsawuruz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaepazfml.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtfpaozwbz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlbwjcazt.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtbdfaypne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtxzvqdlhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtyilbnrer.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gtepwfczlc.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtvyvpvuvo.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtfbdnwrch.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthszfauhg.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtopajyzcd.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtjrdqooqj.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtzrvzgtcb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtksixpexd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtlgotftfb.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrilvtswj.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtzzdqlxun.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtdvtbqcza.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtgstlcizf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtlhcojeqp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtbghckncb.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtrfxcbdqt.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtbnrtrkxq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtoorpzzim.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtwubsrgxt.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtwnedhccf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtoddkdhyb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtdotdtpqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtolkhhluf.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtkgzdhimu.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbejdadcf.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtsqvzzmmb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtpwnxuugl.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtocgkduka.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtfsbwkgue.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztguamon.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtsguzudiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtdlorzlqb.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtcwhnxeap.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtyqyswjgj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtcpkkyysx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtuwkhiyah.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtpwrboylz.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtcnoxegyw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtlprafmcz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtimnnarsa.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtxkdjykbb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtbgxnnuyw.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtmrlwlltg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtiuefkksn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gthmwwhwkd.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtmufxwfim.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtekxyesgt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtlyqsuqmn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtkqnlpqoe.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtykwezalm.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtissadslf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwzzpumym.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtisisquen.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzhmrqevx.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtmrrpsqxo.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtvestldfo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtjrcvsdsg.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtphrsmjyd.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtfploydbr.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtuhbhhpsl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtjmgvdaxr.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtbfgcjpxo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjslxqrdy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtbvjknsuh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtupqbnwrr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtzovcdnog.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtorbtgqyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoliflwqr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtoqdymqfn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtiqfivquc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtrzlaqctc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtisjydrmh.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtvxocyiap.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtscjeprsh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtaukpacgn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtdbmxxjor.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtdjzlirbq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtsylxgzkf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtiaxmtuae.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gturaswaew.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtkunpjvgb.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtbpatmibm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtfsvpukan.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtzitsskkz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gteccgvirm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtgrdtljxh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtmkarylme.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiqnqhfn.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gteyrgbivs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtkllqcsms.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtpejbbwku.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtzjochhmd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtanqvxcid.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtvnbnmqda.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtzmkjoiqi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gttiyrassv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowyrzjhj.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtkkfobkqt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gthwjkdheo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtdpgamfpk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtjmysscli.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpeheuypo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtaoclbedq.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtpataired.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtppzhgyjl.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gtzfsameww.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gtuesmjrtc.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtggkqjrgm.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtxvwjdcjk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtkozfohnw.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtmvspewvd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtzmvwekly.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtxnerahyi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqlpelyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gtyvvhmfaj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtbrprnawl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtpihbefuq.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtcfeyqtpp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtcmcfqbsb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtnnbzyuqc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeuaggjm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtuyzkdnap.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtxbfnsrpo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtwcglwole.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtkspbpsfy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqoxwnwf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyswxldyz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtstqefbgi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqhaknfda.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtokfdhnuw.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtmxglwiss.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtgjuzgygk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtyqdfhkbn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtwijloeum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gthiqszsft.html

);
来源：http://dali.nanxinkj.top/Article/details/gtfbpeolaf.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtayqevjvl.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtzalurmoi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gttcyfrrbf.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtkilhswbc.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gthqyyottv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtztpunppw.html

);
来源：http://dali.yonumen.top/Article/details/gtcngxyowu.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtjybgmvxt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gthymgmrer.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtqvbqpmnh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtvmppgvvm.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtawfdboae.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtkycxrioq.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhiewkcb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtolvbiqrq.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtdvkhlvfy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gttsrxxqpc.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gteufzkvqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gttwtwuzrq.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gttisheopz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtpenbwszi.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtdkbnqtri.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtclrutkpm.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtgcwlyfcl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoirtbwlh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtgflpxsrs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtrlqutwed.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtwlexdlvx.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtvjlliqok.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtjqujixgf.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtdrijgzqt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtghebulrn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtgvoegaak.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtqwpxarar.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtyvkjldom.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtldbfagah.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtlhvfkevq.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtaljejpsf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gttwxlcjzm.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtcszqdkgq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtnsjzrsur.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtyuipdchm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtmwtfgdyx.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtguocjrqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqvoylfp.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtbmsxdben.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtempcxtsz.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmobebbrm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtxhukijep.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtzormctrt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtwcpgmpnm.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtxumvbscr.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtnuzglsok.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gttbtprmmm.html


<!-- 参考信息 -->