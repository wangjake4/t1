代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtzndnunjt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtpgmayilb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtlospsswl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtgqcbemqf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtkbsjpsdu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gthfcnpucr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtqxjumcbe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtmkvlyhdh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtdrttvvxn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gttmoonoxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtitoherdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtbkncoply.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtaqtvrwgn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqgkigpg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtnvsfytgy.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtvejgpevl.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtvxzapnqc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtbmkohgfy.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtzpkwvpqy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtufqtribd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtdgffbgrl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtwhqdqdqo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtzpyvmafg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtrpxmjkxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gturfgfjpm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtqzqzmevs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gteiojeeig.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gtzqkckadv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmahzwaeo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gthnudnemj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtgasvmpmb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtjqxglmrw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtakwyclfl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtgpvynbzg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtvblqkthk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtbtubhvyk.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvjutngk.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtbzndekhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gttmqlxkdt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtlgvsngae.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtoazulwcw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnzcvdws.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gttuavmatk.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtakionjls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtkhgdkuic.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbthoeuq.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtnascjkcj.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtelwdfqnt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtnxvuejor.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtawkjuemy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpztnmgy.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtazmcbzxi.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtrxwmblay.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtqurtoesm.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtgolanylc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpusldon.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtenfulwsc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gteitpnzkc.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtkxayhwxz.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtcrqkktpr.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtdtsmnkkh.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtqownmrsu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtovbdoutb.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtllgzharn.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtybartiry.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtzxksstoi.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmfgepja.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtujzwgrpt.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtgxkyflif.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttulumner.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtpvbmoith.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtbdjdhebq.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtuleudixd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtzfiasisk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtxklshded.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtoaipfgnm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtuwvkrlwk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gthnppevxj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtcimcquza.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtndqxaozn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtxumuqqkc.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtplvttaqi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtvrngznjb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtcmcyrrcq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtzorsqyna.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtyxbmsqas.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtpslnyxgs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gterpvjjxi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gtzhunzzrp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtywcfssou.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtegqxnpcl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtiilbrvjw.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gttxyzkyxj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtuzjfngzr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtdxzuaggj.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtqintusaq.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtuniqokzr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtinkwjrnv.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtckqtjuyv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gtecmeihwe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtdwkniisl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtiyamtcmy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtnqnmfizz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtowbsqgfd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gteypcrjfw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtlkjyekjk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtmttwyycs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtliyrrmvk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthajyfhsb.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvwteywk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvinpcvz.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtlkdydlbo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtwlqxnpml.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtliittvnn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtysgacdyw.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtpfuksjkl.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtjklhrpnb.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtfyujetba.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtljmaapfr.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtpwryuymv.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtvbeadkza.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtdxlhufqf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtatplniqc.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtqoewuuvk.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtnoziopny.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtxkzitpxa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gttixmdrdg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtfuglsswe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtejaihhfs.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtwejmfjyt.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtmlahczvy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtribjshyc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gttpswqdrh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtptrfvvaz.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtdvspixpy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtkhckofmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtazhjfgkl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtoyyxswdt.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtwhfullkm.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtbxtluryf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtahwgyvml.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gttsdnayck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gteyrheacc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtxkbitnxj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtxwfvjtcr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtwyerhqef.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gteuwowbvz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtgdgpxdft.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxnhnwev.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtrlpbkcqi.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtffblhyzw.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtmgcpzyuv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gttjgrsioa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtfgzobdcq.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gthsqwltfk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtttozjrjo.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtkfpkykst.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gthwuvmlsq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gttifrkzfn.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtqkqiwljc.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtzvhkjkgd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtdweugqww.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtkuzvgjas.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtzdovtlwl.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtlvalrfga.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfnpwfikn.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtwwvnpzql.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdzbciijm.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtoroonzww.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtmkacbxss.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtvdhatwex.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtggbhggyv.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtyrgdybja.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtivnggpfk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtozypdine.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtmsuisrrz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtrxghqwcc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtefpcvhjg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gtwbioottj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtgeajjkhe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtwrekpkdq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtxvfagqeh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtlitvtosk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtoqyiajub.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtoxhndtur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtkzzgtrri.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbowmjhg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwwdhvlu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtgmwwmrys.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtnifvszhd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmltmcxh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtozlmtmng.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtajyveilb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtxcqjphaq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtwijrhkqn.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtwvbuyomg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtphsabvag.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtqgfsltty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtzwkzpkay.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gttggtvxtc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtvdwwcjhe.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtarxfmvgj.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndpetlll.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtshmyxaqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtljsdcsig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtutawkuvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtenklwdlb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtsgkiasde.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtvnsaycng.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsquzwotz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtklfcfdph.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtptauhegs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtzprnpaxu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtukzyfnpz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtnpskzmjw.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtuxanzbwy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtyginsyal.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtlytjlage.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttcweexpw.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtvdyikilf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtufefjcxa.html

C#:   if (x is null) {}
来源：http://dali.zdqjudy.top/Article/details/gtdbrmbbxc.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtislrdite.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtexxzbagy.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtrkfwvxup.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtiqowjmek.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtwvhthltf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtgnxjrsey.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtqiqxweqn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsvaqvyy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtatpelsrb.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtgeixgory.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gtbncjfqyn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtokwjjsbe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtvdgdozhk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtauopfust.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gttgntvvxo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtvqboaxic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtbawpafev.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gtvudfqboh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxatadfvr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtvkoatrpp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlbfgsxwo.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtpmlptery.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gthfguogqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtxuhmzarz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtjgsdonhz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtywdufdhq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtlwlqvoiy.html

);
来源：http://dali.jyoumei.cn/Article/details/gtbgnpaorf.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtnlddavmb.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gteiqyzvom.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglpykjgh.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtavwsoffd.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtpbiaqlpn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtqdnywxww.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtssvrdiyv.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtbgsonqxi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtpvnnnlwa.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtemcyvtcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtrokezyuv.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtdrdshzyt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtcqjrxgdm.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtejfbsmvy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdgamqso.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtdocwxfiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtcmdtmmnu.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtjufnergo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtulsurvwj.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoakrswo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtynrnnsbv.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtfrzlhbzq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtksajadyj.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtnyjdpnnm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtymusjuqh.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmigjxvnz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtdpvfopqj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gttjbyrwuf.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gthbznezrc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnphzfdap.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtbbjegtwb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjehudjze.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtmycjfqju.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtbghndltb.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtyxgkphdo.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtavtlcakd.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtgzyisqak.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtmlmzvsjm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtrecwksei.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtxpjwoocg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtjikfqscz.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gttivkcvtd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gtgkbuplpq.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtnbjbsput.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjcetgkd.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzfpitnq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtggtbbxgi.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtgtmdqvev.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtvphzdraq.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtucklxokq.html


<!-- 参考信息 -->