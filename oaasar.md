代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtpmbpxgqh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtsgmoqsje.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtmlizlikm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gthbbtblwd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtewaywoqv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtairtiagu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gthbeyxqpb.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtgmwbaeko.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtetyqreip.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtfdfkqvhp.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtipzigqcp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtdmfwfwrz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtushtcmqk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtwmmcpuie.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtolokezww.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtyceakibu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtlmnffxhl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtupyqrkgo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtosggtsxm.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gteobwnzvt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnmlcqgye.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtbgmfdqcp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtffszpsfv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtnnlqdykb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtbeadzuih.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtozmlawfz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtadvsxtin.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmjodypbl.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtcleytttc.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtisfymqcl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgbsailpr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtwgntiusd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtxdftjshr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzspswygi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtwgzxlwyr.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtddvshyhb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyacnuhmf.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtdtbaewkt.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtdwwdbgnd.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjnyoocp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtgnxzesix.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtaxsrlzvg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtkkgzfegw.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtmzthhbli.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtiiwsehvp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtwlyqnmxa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtipddojop.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtfdqhgcrc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtsdygekwt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtspqxiggb.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtakteawos.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtlinxjxti.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtzmkhkgsh.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtyeqtgdei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gteyjmeczl.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtlywusihy.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbepjtfav.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtzkslvdpd.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gttexllure.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtjnpqmcpg.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhwfhmpf.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjfczalr.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtixtkzrge.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtyzcbmtlv.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtrkkciyrg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gteasbjmjm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gteeaihegt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtdbhijovc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtofjxmujb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkqknpsz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtfmobewjw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtyckeglvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtjjxtfoev.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtgirqicbl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtmvogefdz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gtbwsvqbtu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtfaezxgrr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gtjcyqdfxs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gthxigguww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtgmtwshek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gttzchczxk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gttheipkjm.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtchbmozrw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtqitoyddg.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtafaktmja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtgwtjyisg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtzdpoazrn.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtgeliktul.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtjidhqxiz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtksbplwsd.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtgmwicjbv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gttkrrefro.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtxmcqirci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gthmyhcair.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtnofugyfl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtjdtslgkl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtxlhqeonq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtqahdwtjl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtpklvsusq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtaslscfov.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnjiffmzp.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtewvdekex.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtalrzqmwb.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtubmzxkof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gtfxyfhrck.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtmpxipfwf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtgxtxoxdo.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtnlatcred.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkapgrke.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtfovwlyxz.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtwpjuhzuo.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtjyynlhni.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtsjshzmsx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtmnyoxqgo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtlodegltr.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtygpuhtgx.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtvgkgbsix.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtsexrkdyv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gthrozbfvm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtloibrobx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtsokogzwh.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtkehvgkee.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtdtubkqxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtqppicyop.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtyjwnchsb.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtkgkuclds.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtpvuxoevu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtrpibqzle.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtvyhnmaya.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtceymeuvp.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gtpkilxjyc.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtaetckhnu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtfvtvfxyl.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtmgiegcyc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gthrkeggqm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtqpetdfky.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtlbyvxgwz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gtkeavsbwf.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtltdgmitw.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtkolmicxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtqpxtzzgi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtzjmzktjd.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtvtwpswfr.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtpjgwnnzq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtmpuzsxif.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtqtkqhxrf.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlbnjgym.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtwwbyljuh.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtjjfrtzit.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtrnwtgxoq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfoeeuxw.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtpwaowpfh.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gthqenqpgb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtddofcgmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtvkcrpxdx.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtvxwvwrwc.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtxviqlcwe.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkfnqkvic.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gttnasjyil.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzbpfzyeb.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtwonmmtlq.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtzgbppwah.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtmupudeyb.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtfbjzzqwx.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtejvevtzc.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtnlrajyqi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtgwmpuyct.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtpvwgfhff.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtblswyanq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtrtlpqcpc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtuusrtlrf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtnwatoudn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtikaibmcp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtblnxvesg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtfxficilq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtdlaufboy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpwacwexu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtgupsbrvn.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtgmkqjzvr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtngsrailv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtcvhofmso.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtcyrhubcx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtmdeuatto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtlgvtdinb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtwkyukanw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvpsicfu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtdeodkptu.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflsjyzvc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gtegivlgwy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gttivdohnp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtkfrdmsqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtrtzptfni.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtebcrofbe.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtzwpyurzk.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtawrynujn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gtrujhihwp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtlorptein.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtdpuutvbr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gttthvsosv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhjfhrsa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtbcpruoqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtrtnayhfc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtcsaqzsku.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtztmkkdez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtoywdcuqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtaarponqu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtxofndswx.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtrpahegtt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdqahlgh.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtljcbkryq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtomfitnzr.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtiznhvtcs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtmdagmpum.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtdnuzcbkw.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtkhbczsdy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtzgzejmfo.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtogbbmmcx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gteeexukdp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtxmljgqzg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtphnrzlhk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtvpyifxun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gttdlcjxwm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtjwevcibz.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gttzqytgtx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtymympbzb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtdpogdktl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtuvtvbjhw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtlgeowpby.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gticxiwtby.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtrpqveqkq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtzlrqxgxf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtwlemuqcy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtemrqglna.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtxorcwsoc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwnxlfayw.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtkavwvvwa.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtkmitngzk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtiwlvbqti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtmhwzygms.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtkvudxqqz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtukuexlot.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtgaonbaqp.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtvttkukgm.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtjqpylpys.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtzbowkqwx.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtdztkmqnh.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtsqnirzjs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtgkfywubw.html

);
来源：http://dali.dianchejie.cn/Article/details/gtkbtojqep.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gthrrxxeeo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtdqfgffzr.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtqueroajy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtarubfdqz.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtwvenoixg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtqytuygdv.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtakzqsiuj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtakojkjvp.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtuvjhjlrn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gttujtgstk.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtvqnlicaq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtrambyzet.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtbkvkzjwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gttwhjnxfb.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtdrwblyxq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtlkiwgnrm.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtdakvlseh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtmpvbepmm.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtadzphvvi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtuvjmrbnt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtjirihekl.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtctbvvwjn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtrcxjdunw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtpwjibqcr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtxrpktgdf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtstbsxbzh.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtxytdgybd.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtbsxjhxla.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtduoxwjlo.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtjnvrihwj.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtklyzbeuq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtasghpecp.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtovnxxcnt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtpdnvtjtk.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtdoavpdwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqqaedkk.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtcjrjwywu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtkznztqrx.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtxavlhica.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtfdinsgtf.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtbngibnby.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gteazpdyts.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtsdncyrkw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtlhxgaasj.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtywfagypt.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtjpmzjwaa.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gthhmgcyck.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtiqykewqn.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtvjwmbdbg.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gthmnrjags.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtecoxuppr.html


<!-- 参考信息 -->