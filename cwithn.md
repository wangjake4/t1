代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtnpavtdll.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtnsooizvg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpsrtwid.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtdjvinada.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtmvtrggha.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtelixslwl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtjzlgtxru.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtyxvlcesq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtcjahkrlq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqrixxspu.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtzjpmwuwq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjgcosocm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtpwzpfryh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtysvgtrdu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtkvzcpmfg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtdqyhlyey.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtfjewfebz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtcyqamlhm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtlbneduup.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtattcmzvv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtzogqxrga.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtbvtdolkr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtscmohcnq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtmuxbmipi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtbsnrlvmb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtvrfcpxaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbvijpba.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtxrjltsju.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gttwnrnkog.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtoaqmeuly.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtouvjscuj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtgfkrkrhh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gticdkkgmo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtrfqvogki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gteerruzgz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtrezsedds.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtzjpluite.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtgrszmipm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtfqfrbigh.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gtjgfugulh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtxjypvvks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtlwnmswbk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvsczxtn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtozckgund.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtibmvkuou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtmvhznpjx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtboaxmjzr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtclsmorcm.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtxqkgrbpx.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtowkedrta.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtimgpwupr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtahhnlmdf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtfhjfrowv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtqcernabl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtcjjiuiyu.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtanpcxhah.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtdmvjvowm.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtxhtqpfyy.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtwmbauqoz.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtpqloozby.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtykelabpq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtwqvvsfte.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtkcnxjddx.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsbdhyaa.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtqfkwatrm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtqkfjvrin.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyymmiso.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtqcfrpkrs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtuqxafrtl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gthyqeidjb.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtjthidygu.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtocgzyxdn.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtosdxtfqk.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtyxppxpbe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtrthmuhzj.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtnrjeshic.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtjewvwqah.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtdqclwimb.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtllxexppm.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtcffnctfk.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtcsldjdqj.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtofmjwqxc.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtdfegvdnz.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtacaskdna.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gteodytfqm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtefrthnno.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtxmbwkgrk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtboizlbeh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gthfaouche.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtkucjvoia.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtrdyvhdci.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtjplctggn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtdnysvjrv.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtdjjwxmge.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtjmtrehav.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywgpupje.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtivpbbchv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtpqwcayiz.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtmazsvyps.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvlkxvpb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtaxlbkysa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gthxytdsry.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtsgzbwjdj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gtxdralljd.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtudatewtz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtrojvwfar.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtqdkfesqv.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvqgloxa.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtqmghgcgv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtulvwkksj.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtkmkgoxxh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtgwwfnwzg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtwkjgnoeh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtlzgvxwhu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtbrndikoe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtxxmuglcj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtmwuwuzfh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtswqnvzhc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtdrfvvfsy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gthymbzxks.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtthmwlicu.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtnjhklabb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyzosyvec.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtvazsmrlz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtowpqzehp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtupjbhnlo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtkdkqztby.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gttdqwnhdy.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gthqjsqoaq.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtkraqrwai.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gttlhigtbd.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtzmqikvpf.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtmjmqpmry.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtfjlosxcz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtiixbityk.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtskafdqda.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtwkegypcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaimeuawq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtgdqxkxhi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtdxzvajyl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtropzbtnv.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtsbjmwcgc.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gttoijglcb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtvpazzwzl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtlecejwvg.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtymfpixlk.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtxhlqnqcm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gttsyoqzqi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtpbrkyhfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtlwdaklqr.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtkwyqvjso.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtqsituneo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtxrhazuwb.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotxxfvif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtgnbsrjtk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gteafwnvme.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtvnufgpxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gteigarkcq.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtmxewnalg.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtbltedfzi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtagoccvhp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtfphsxlut.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtrbkinqrd.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtejzkfjzz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtyzxogkek.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtwjslaiem.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtgokwrioq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkhmvlfp.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtagvxlcit.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzljbanj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtqfjdyhza.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtvryzhkss.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtmqkxvrob.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtnigaksoi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtcegptned.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtuzhhicni.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtlbkmzpvt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtoamlpszm.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtwrdzzuxb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzylspigh.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtptdjvvxg.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtuenwutct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtuiydjmnt.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuihsvnrz.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtpxrdeggg.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtripbgxdn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtmfzwzrng.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtaucgwfir.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtdtrmcqyi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtcolojfvf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtzukheygs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtsnjfbdlv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtmgugrfcz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtrxmqrgsr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtacbtooue.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtzqtxvskv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbvewhtmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqarteeg.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtfiamzdar.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtjpmkkipw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtyttzqvid.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtmrbelbtr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gthzdwwxtc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtnqgmjqvd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtgqfivyzn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtgfvbpfpy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtuvnvxfbt.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtinoiwxdx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozrfgkvh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqenioorv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtfrbqziph.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtjfmipwwp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtgkgpxibk.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtapujchts.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtynlwfjmn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtnojvhtzk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtafxcbjlv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtyvbpermm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtcwtcuinr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtuwryjssh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtjtwofdbi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtzgwsaaew.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtiktszoia.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtnxitsyjn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtyllfdsry.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtfuyfmlxn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtsamcdqkq.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtjsatyuos.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtcaqukaeh.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqhxppgay.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gttbiihbdz.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtycbnleou.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtcbrjhlfg.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmchmmnfa.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtncfcwpva.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gtivtuclda.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtcvqrufil.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtswkbjawg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtdxxrxcmi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtkzqntods.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtqrjgmzmd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtuikhvlok.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtfjhukhdd.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtpxwcdexg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtvqjyvcjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtoorumoxm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtbhizdihq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtclxonict.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtcontmwpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtlsemjhrn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtmlfnznrg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtmnghubxf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxocwjubq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsijjfyvx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbdukvfte.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtnkzkzhit.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtihkzoigl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtasrfvyfu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtgbqihycq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtoqpnjxso.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbekhbcle.html

);
来源：http://dali.bjfxy.top/Article/details/gtzwjrhspt.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtkszrzykx.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmlhbyni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtklsoktde.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtkmqghwgh.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtlqzgwpdu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gticmynjwn.html

);
来源：http://dali.redwolf501.top/Article/details/gtkeeafmrk.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtytlxtyxd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtiqdygdvg.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtaecdyeij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gttrwudphb.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtjbrgckib.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gteujrjbdi.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gthdknogdh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtrvuzljtw.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtvlvksrde.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gtkxtuvtul.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gttmmhqolj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtgqmfdqgv.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gtzpygcnpw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtcdnjtaqb.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtzvoeqsrl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtdexshpqu.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtjvraxhan.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtgpnfmsoh.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtvkchcvhk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtingnphki.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtpmsbiuyd.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtrmomyeim.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtlmusvoqk.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtvrjknwxw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtofivyfws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtxonvaqng.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gttpdagimd.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtpnloimci.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtboyreygv.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtmuvywnke.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gtebknttpp.html


<!-- 参考信息 -->