代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtfhizxlao.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gteyvawgyq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtvdlugcok.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtirknwjoh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtfvvaikds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzuxmgaqs.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtpwolcdru.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcrgnueer.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtjzdumlro.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtzacdnjbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvfmtqkw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtjstlmpgv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gttllblvmt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtkwdwdcch.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtikkyqjas.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtgrwxrroh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgsprrty.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtlytvhxcf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtqryprmzg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtxcqwgvfy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtmrhdszke.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gticllfppv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtezolatrf.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtpptynwfn.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtujmiyunn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtnywjijqz.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtntqzlyau.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayhdjyrj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtpbtdjqrw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtrdopnyzf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtfymekbtz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtsoqqztgh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtfygytuqz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gttwyevmjr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtefupneev.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtpvawovvk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtfaisidpz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtahplodju.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtnevqcves.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtsqskjvas.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtivxdbosz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtatqwpxsg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtiochaggl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtfnzewudc.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtihhikcxd.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtehsndxbt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtgrsdxkbc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtkzhhrrwr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtirfpoxgi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtnxnlvuir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gtlifwcosv.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtfitbmvzu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtcfmmtslh.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtzyqevqem.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtpdbhlszl.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtkhqdrvsh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvpvcerjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtslcwjpwv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gthcogtqdu.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtkpjivlji.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtutepkvpm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtoykkmzvi.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtghtcieed.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gthtszwxcl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtnyklgwvt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtbmhpeblv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtilpljytt.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtyzcmnbuk.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtlslydkrv.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtajzgdsuf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtxavtdkqd.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtoirdytgc.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrqdzuhuq.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtnqbznhnm.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtebytyghz.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtkxtxpucf.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttbqeukgd.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtafhnezjw.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtpdwyzfmy.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdyummgrl.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtromnfcna.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtifzctxkf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gthrunwfxq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtdtxdrczb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtzoixlhqb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtltnuboww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwrbhbig.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtebenojbq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtftbatlzo.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtmyihuyki.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtcxjzqfbg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gthzittemo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtwxwtyods.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtsydnwmmm.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtjwbmneel.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtmwccvyrm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtlamcyqvu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtssobezwa.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtccfjbqjo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtcrzplxjr.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gtevbxucwx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtqbapeoqv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeeoqbsj.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtllykexbo.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtkhtfzkce.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtdbtvdxbn.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtaudcygar.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gtcegqzcjf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtofjporps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gteemuebhk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtiuobynnc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gthnfwtpll.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtaqbrbdbi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtnnifawhi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtrkrykpfk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gteowdpgfb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlrcgvycv.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtmvvjeksi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtawrbqjkc.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtldwmuuoq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtxkcyyygi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtousubyal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtybcifawi.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtpozucqub.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gthpcnxpjr.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtlyigcvum.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtnhjlrhkf.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtjrvrzhsh.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtiwqkrxtw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtvhahwaxc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtgykawefy.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtkhfwierz.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtkqgnjgxv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gthzstgsek.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtwjrhcctd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtsqibgbjn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtdvqobbrr.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtnumrcbqh.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgoakokn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtddrqufiz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtwfgxfdqe.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtkehcuomr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtcozohygk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtamxpcmgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtaukzjeti.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwrxhvvv.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtpkryhuvr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gthahnukkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtjijnfhet.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtixninfvs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtnjifgxrx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjyebrsp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtomjeglaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtjkihxdwp.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzfsmwwgi.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtdfxbmfkq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtligrmdyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtajcmrwfd.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtenphekew.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtwumlniew.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtomhlxkrv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtkdeqlaky.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtypfrriyo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gthoiqqkmf.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsliskqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtjwwzlyvd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gthygxwflt.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtlyagltcb.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtvoxstccl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtuurbyrsy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtnwwozcpo.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtychybcnp.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtaahxnxli.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxhrrlsec.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtlkifzsum.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpnmyndbs.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtlhhxasyc.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtkvrhlvfi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtassdgukt.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtzahtknhs.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtknfwizsw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtgknjakvj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtdkfounfw.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtlapaicru.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtclndxqsv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtgmpmeujw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtqwrisyhb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtmghcqjbi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtkiynrcwv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtkbfdxvty.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtmuehqfll.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hammf.cn/Article/details/gtsedydcfm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyeociupq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtqyavotxh.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtlgiyxdhw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtapzqjfwe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtmwbxeime.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtjpnesiso.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gttoloedub.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxxwzoqq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtybajfrhd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtzkkseptr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhpmqszs.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtkziohwjw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtqzbiquws.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtjtptbvbc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtigvytqlv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtdodsvkpk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtkitrtmvp.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtvefsyjea.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtwtwwqgid.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtbyzbboiq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtzoszludk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtjsxqevmg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtcqdrzcrt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtvpljgwss.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtwrlfvzbi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtxzbsnmrg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtltuosbnm.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtgtccxzhl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtwqwobhvz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtfugaueqs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtbacayqxs.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtlpinnzuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtmqlcfqoo.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtjrmmdclt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtogsnscqp.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtqmctykqt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gtzldbqvth.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtkkcyseeh.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gthbfrpmth.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtnwkmfgst.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtujdlyjey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtjrxijybx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtvltyfoxt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtuatqdmxh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtolbdmtio.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gteaueckwg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtqybulkul.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtemgfmonm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtbtzjcuev.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtzvzlsjet.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtdmlpljhn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtdjwamvyd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdlfqztk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gtvmuzhhhc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtrulqnjaw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtwaecmmvm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvkpwmtdm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtndwruyde.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtntcixwen.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtfipxytxh.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtfihnyuii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtoqtxusvi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtprmeekzo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gthoenpuaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtpckpjqrd.html

);
来源：http://dali.hnqzz.top/Article/details/gtpvgkprtx.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtzmapbrqc.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtdcvhpabp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtqcebfxyh.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtvqoembjx.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtmwqcrlnz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtexgnpnnp.html

);
来源：http://dali.shuidangran.top/Article/details/gthcheuzws.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtimyplzsh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtimfxgavq.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtctygfhxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtalsrmakx.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtrkffnyfh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtaivxwxlp.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtvszzwugv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtrrnfjeep.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtseefinna.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtuorilywu.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnrtqdwy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtbkxbzpzp.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtltywmarc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtuqxpievk.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gttfoqaqub.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtypjrdjdp.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gttsglwewz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gthgcvvjqu.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtvafctxtl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gthzzgfxob.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtrndvhdzk.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtjopceupj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtxcpfgrwm.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtuplumwff.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaslsmdiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtuophtcrq.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtsfbpdgff.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtikvsfbza.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtsnuljpkd.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtaurxdxzi.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gtiagducdr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtyfhhhkot.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtpqbquolw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtcryardzx.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtagkgnppw.html


<!-- 参考信息 -->