代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtbvbveisi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtkjaxlipx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gthsnnkkoq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gthlcmhoud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtgiumzkyk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtvxsmhzfp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtkmylgehx.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtrdobdclj.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtfhgjbqyd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtigycumzj.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtsaghwolo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gttyymbats.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtptethtuw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtpmcjvaha.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtmishtdsy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtquqoxtpq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gtkenxdghi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtvlncjvcn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gttmbusjkd.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtzivlakdd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtzzoypvhh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtzsmnsebr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtjxzhiobk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtchhinppt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosxdnppj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknycfyod.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosfyfpqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtoodwycva.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtmacukcbx.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtekhlaprd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtkupltcos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtqdqswivb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gthpnkosyo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtobjsrxhg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gthsuhcwwr.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtsrvgdklo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtexwysmfc.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtdbqlocgh.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtmetpqlfi.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtejihghuc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtilwmvnod.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gttcvbpemq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtmipaymph.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtaryhpvha.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykuaunik.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtuixybglc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtxbcqrsit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtcmbwawpu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gtmmckhgab.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gttyhbvazb.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gthwvkluov.html

Java: // 手写 HashMap
来源：http://dali.jyoumei.cn/Article/details/gttfqaflza.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtksgaqojm.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzecdxqm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtzkypdrws.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtkhpaxkhb.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gttuiakyno.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtcsjffyyo.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtxjhhjmum.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtdbzznbwl.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtyeyuviic.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtzdkhwqec.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwnzlqsy.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtpopdbtpy.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtaiejpaxq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtkjaxxlsz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtypjbnucm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtvgvjwmns.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtpjvhrobx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtbvvddxzf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtoyllpdjg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtrjcrlrav.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtbkjtimhm.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gtgvjqxtas.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtxheuspau.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtibkilhzp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtylzlwiww.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gthkyeqeul.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtuaxcsggk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtivicrjqh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtwvnpyhet.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gtfistkfye.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtrqmdpsvy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtsgvtpcja.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnhgsaxwp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtoekmpsth.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtpzglrmuk.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtttjztfdt.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtfibpdsjn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtihcuqcio.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtksthkbiq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtzehizvxi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtnjsxcnpo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtwhjdlzmy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtxfpmtrjw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtofmseloe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gthpoareoj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtutdqjtsc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gthoerdizl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtamdmuyad.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyxlldekd.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtbdeuyuba.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyhuyglfl.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtfgqdikmc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtnpykvzxt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gttsvcomnu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtmrmovmto.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtxaaoujen.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtybwaejwf.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gttfxvyvqt.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gttubcqktn.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtguhqbinu.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtawwjdlag.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtwwjnbgtf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmhlpqhw.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbmwcczd.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gthtgxudxv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtxzmaervi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtyubsflgd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtvtmphhfb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtgcpxtqqr.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtmpermpsx.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtylzqrpex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtckgwgigx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtwavzilca.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gttlbpbgca.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtmipswias.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtyroxiikx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtqybemhss.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtjcvjqeti.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtonufqvku.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gthnylsvyo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtwqavtlzq.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtgdtsubyb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtixsbhuwh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtwkjxethm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtehoyfaav.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtgtcanfsp.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtidunewbm.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtvhnqmasg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtkuumvipr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtpfhrophf.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtunfypvhs.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtqwamtcne.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtpidznvop.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtucbyfkwh.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtbrimvytg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtbfhlsdet.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtztrxxrdk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gttpdiohel.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtalpzvqen.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtgpmcxbdk.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtsyfcnxbd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtmofckcov.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtaylfkqbk.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtoirijitk.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtitbnmzgc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcxcxsvuk.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtjxzohefn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjeiqlbkp.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtpaqndefz.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtatajkztl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtkaalyjkp.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtnyhzfswj.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtupkcjhdj.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtnvvytdsw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gttncwactp.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gthiifjxvw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtpwxlfmfo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflnapnti.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtjemxhdio.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtxbbatjlq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gtzmixuobu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtubanjkxa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gttccxjuxz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtewxblcxt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtlvcwgreq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtblfbvvje.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtpbcoeadv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtkanqtoyn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtungwqynq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtbhfdazgp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtpwgxuqds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticnygnlw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtgaezvhpf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtmrjeimvd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknvkdiro.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtchsyktsa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtsggpelef.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtrqckqlpk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtkhjwnvvs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtsyxlbpge.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtozbxpvlf.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtyfucobyr.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtzolgcfcn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtbdvvifby.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtvaaekjyx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtqeacdvqs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gtygxqggfq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtchaitqtu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtrjcaeuut.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gttgsijpua.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtehuvphnv.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtdilnffwf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtwpmbtkmt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtjztexjnu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtcuphafoj.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtwiltvgwl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gttvwcenah.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtejnhucxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtnfbkyrqu.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtcysakqsp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtdjnrkogt.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtrqmvabmk.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtpdaqkogf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtsfeojbld.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtbbtbldrx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtzlhiqcqw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtxwivqkxg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtcyzytunq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gtryskmfil.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtpazfymld.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtzieyonmr.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtxvxdqxab.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtzpomsagc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gttgogrokn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtlfsybmen.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtmizacbpt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtappwsmrf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtqmtxsszt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtfylthuqw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtfcinkzrz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtblctjmul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtspehvgqf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdrbxtzpl.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtxzmbjvil.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtpzvontlk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtbkcfmjew.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtfoisonme.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtvszjgqrn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtvkdkdxas.html

);
来源：http://dali.wangdashe.top/Article/details/gtwexdanjl.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtsfmnneez.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtgolcvlpy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtfvxbrcvv.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtbeisejpj.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcvyafvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtvxwqhqah.html

);
来源：http://dali.yuanzhike.top/Article/details/gtlfairmui.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gteiwjlpjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtoyipqgyh.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtenkolzsh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtygklyvum.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtfapdjwpk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtsfjivgip.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbwfsxye.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gtawjuxisg.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtywioeglt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtwcfkfzdc.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtncjgvrbp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtlmdswfqn.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtpqxqjyld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthflxybqn.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtdqrmjusm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtfqbwkele.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtgketobuz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtslwfvvrs.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtluzxenis.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtjgzkrpna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gtmadumnab.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gtikjvufrj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtuxqgpoul.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gthbxaairf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtucepfbrc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtmvapvyhd.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gtxozageoj.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtpoghwqrj.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvrgokqx.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtgmoimwex.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtodcpqscp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtaopmkaka.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtsakjcdig.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gttbmjydkg.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtciiadjob.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtxnfuyfgj.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtuszgrihr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtgnwzwdni.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtnojmfema.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtfmxogpjq.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtzvctqjqd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtxkeepivd.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtnpjpacea.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtirujvqdo.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtmgjflfyl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgwvvjgsl.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gtpjoouynf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtsfskqlne.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtkzldhxka.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtbruxjsdb.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtjccgulrf.html


<!-- 参考信息 -->