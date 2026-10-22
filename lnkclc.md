代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2zaybbxwk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2dlhykngx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2tvyzpviy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gt2jissiczh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2oizoglib.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bisiaqkr.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umwdjhee.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xpicsuom.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gt2dlrymdfb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2rgwlaovz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2blkgzwba.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2mwbfthtp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2wiwhlkiy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlddzjbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2yvfbgscp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2gslsarwf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2wukcgoxq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gt2bgahnqnm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2ibazsqry.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2acxndxsr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2hyzltheu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2kwunpxda.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gt2ulnxukne.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2qlpzgjfy.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2raaypnsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gt2vcmfpzrt.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gt2wihamous.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2ucnetvhr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gt2bigytpsh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2rekbhzif.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2blrownrj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2fqnmkrqf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2zrqcabdo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2qtnnbayi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoqizlup.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2bwseefbq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2qinfkvim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2llmchbrx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2nknrcljc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2jhoapdic.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2pcdfbweo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2runqiikk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2hrudyhwb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2ybazqqyk.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2hcgfbecz.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpzmxkqd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqtnmcja.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2ycomkisz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2hrnzabaj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gt2ladfcjex.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2jcdmwicf.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2giockteu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ujntmxzl.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gt2vzwlughk.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2pajdcitp.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrdburdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2yokpgpxj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2tqqsfwqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2miyjxnzu.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2kuwhvkkw.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2jctyaubw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2cfktyihx.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2seuwznih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcecczbg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gt2zzmatmzt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gt2wcbwnrmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gt2dgnchlag.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2bdoqrdoo.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrfsudgv.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gt2sftyuwys.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2jgryrnck.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gt2iubtqjif.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vraqwkcr.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2mrfzoxwa.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2lehsoxjp.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2umpqrfyx.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2tozobxeu.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbztigfv.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2quanabsb.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2sbulqrgt.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2vswqdcdu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2iwjxzzsy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2cdimjqfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2gwlcgmnc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymbpgzgr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2vajtmopy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2qulcujmg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2yxlqenjd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2idkusinx.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2tjqemgwm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gt2vpcnsfyn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gt2ydzedkge.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2jwqmkpao.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxzdysqv.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gt2lkgywluw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggwtdig.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gt2vorkfmuc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yancioxs.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gt2xphykdpa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gt2ypxxzkdq.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2kjgjfjix.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2xyddxhcf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2dnbgslee.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2ifdwstrl.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2welbcfxc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gt2qhqpmphh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2egryzaea.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycdagqvj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2wduznxbi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2yfeftbyo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2uusqntlm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2nlyuwjiz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2cbchybbm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gt2xnzegvmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gt2mvkwmulj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2ounxpzzu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kyaysnps.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2wiawwuru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gcnqbdot.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2vtfrthfo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gt2eznwzsix.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2mhmxnqqg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcfxbcns.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2lqlknckd.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2oydenlkw.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gt2lwzimggl.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2uurpjqag.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2xzjaqfec.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2whasxmqa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2nvmwztuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gt2jtlyripx.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2rbrmfjct.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2afkbgsue.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2zkbpolhv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xocyksgy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2thywupyb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gt2rigpfmte.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilwbzikm.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gt2kmopaxdn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2swaujpwx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gt2nrebxbvb.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2jtpnlpux.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2tkvlhdsi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2dedybidb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gt2bxacnysn.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjdchiol.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qscaydwf.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2vhnlufel.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gt2avzxaaqg.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2piqgixcc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2zmjwzmqk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqozqjrr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2hjcqafmf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gt2sxvicred.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvytobwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2irwfwedb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gt2wjdgdyrj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxnqausq.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2ctljafqc.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2hrpjokcm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gt2wfirbcah.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2azkhgoyo.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2yoqmlvqu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2taarmmjp.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gt2uplcmupp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gt2gvvbmjph.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2jueymaqh.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2pwgpzzag.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2kjfiyigl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjulcohc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2fheebbmc.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tupivrdz.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gt2jaipyjcy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2vuoymfwd.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gt2znuywvjp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2niylkswn.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2gifxrlno.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2ecemuadx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2rwuhyvph.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2eflfpbir.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcwcqrpf.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2gtycoast.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gt2ljtxxfjd.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2snozluhj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gt2zycbizti.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gt2tsghqxln.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gt2vonodjdj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2emcdmuub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2phdkwmzy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gt2zvihomqn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msfbgkwc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2muxehdsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2bweeqcer.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2huzggjys.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrttxlid.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2ywanvmak.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2ztfdbgie.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2apiifqmb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocgfmrdg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2yragredj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2pnvkcfer.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gt2twkechnx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2zfqzpfzf.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gt2wsykyimj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2weaphqwd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2bvsjnujp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2xqkpseqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2grdueilp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebdcfaal.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzosoeln.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spfckfyx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2puhxaqjx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2rhpbpxvp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gt2lylybhfg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofohjgfy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gt2zifrgqzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2igfzxqpf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2wnajabyg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2tbamjsqr.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2hhfkpeiz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2gpttvehl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gt2uqtvovfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2zyuacdzp.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yxbcgjku.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgkcnfaj.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2xscvjlgk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2oxvgoffd.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2zjusfnve.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqbtugfc.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gt2swtfpxma.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2fjbjdvxn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2gqpsjmrw.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gt2fjchagxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhkfneyz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2mmpwpefe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gt2tfncxelh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iunirvqy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuzncnrd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gt2ldjxfvco.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2bystzcqx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2ybjjvibi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2fqcosddc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gt2gyymlvfl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2twuhtmep.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gt2ggukjvty.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gt2tigsntip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayitquiy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2gtamtwwx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xksimmhd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gt2phazoloj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mhsuzftu.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2fbfiiogg.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gt2jywyoreq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2mqzlyxfv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2clyiirnd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2tkglfyrm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gt2rysbmiuq.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2wrbneezo.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2xkzmosbv.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2ztfhjnbw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2mqjesumy.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypnbrwwu.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2yhdojnfo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkpkwfag.html

);
来源：http://dali.shuidangran.top/Article/details/gt2sofcwyhj.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2ihwwdlnq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2riorpybp.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2jtmzvcwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2srgvdtbx.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2ibqpjnwg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gt2bmqypdsy.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gt2fwfdmfiy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgxvzxt.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gt2muokktmv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2ocezyhxy.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gt2temlbfrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2ldemfnco.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gt2ugvzbuuu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2eqkhjazi.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gt2gvhixgbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2bolsnmgk.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gt2zgeslvbe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxxazfde.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2gfcodjzg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoeoqztz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gt2zbmyqvpe.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gt2kqgvcqmn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2wbftlqgu.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2fyjsjimq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2aieusbke.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gt2mlnaivza.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijegdfuq.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwblmzgo.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gt2hpvvzwhb.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2gkqnevdg.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gt2hzmqstbi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2vcisruke.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2laxaatrz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2ghbzjwis.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2tqwvaekj.html


<!-- 参考信息 -->