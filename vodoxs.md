代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtwxgxsugr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtgxfpcnrf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtphcwdnub.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtteycspsf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtzyfbyexb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtophdyqjn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtotxpzqzp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtzsreeyoi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtctltyhji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gttmsxbeia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtuipdthqn.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqswbidjf.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtaqfxlszi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtzkwbgnga.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtosjlnhdd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtjklwidhq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gttfhazlzq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtuexsdsag.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtkronkmeb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtjkmpxily.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtivitqcnx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtpowsvpso.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtyfwfkcxy.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtsnhyyihh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtfalukgvl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtluzbrnyq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtttsyzgur.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtfjobjlye.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtihuuglaa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtgszjqeml.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtaadsnrzu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtacnuhduv.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtjkhudpew.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtilkyqhvl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtoouqckhe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtqskhdbif.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtrsmulefi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtuepwmege.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtczdvfyty.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtfyigqyru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtdhnlswzw.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtkjdulcth.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtytkvijqs.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcklcvjky.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtewengnoy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gthxvjtahy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtkcyhhugd.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gthpqhbtvq.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpdgjwix.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrfjnbip.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtrxpstldj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtovncvewg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtxecfgyfe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtqptavetj.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtvwaurrde.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtuagcvfzg.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtjsfabfos.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtrmiunimv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtwksuruop.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtpijjzakn.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtlrvapqpb.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gteulvfbpc.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gttxjlwzzv.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtrollcodt.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtjgmpagwj.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtfpysgssr.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtcsyywudy.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtnkfhutwf.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtcoviifjm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtzszdsdul.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gthukcaogn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gteemmxesr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbdrbyvo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtmpfkzsew.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gthxjclwnh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtejoqmosi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtwawwnhwv.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gttlfncasp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtiupgpfyq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtwqviwhvj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtgamthinx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtydcetwot.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtvfilflxr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtvxazyohn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtbqxlxxpu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcvhsfbs.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gttknhcwxg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtfgizuiii.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtuhmjhsaa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtxihrlqjx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gteivpduys.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtexwqzrdc.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtgxdsxcxn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtynritzed.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhqvhiwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtryuyrvzm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtwfilqmqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtphpjsrlx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtcrvzvdsb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtnpomcdhd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtrunjybzq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtffuytstl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtwnlruxcd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtiajhsvak.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpzfynsle.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtamvasicu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtriabumtm.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtqogksemv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtidgfqlgw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtgswpyapx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gttfbzkszu.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtzzwdoasn.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtmgukwign.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtvhpxvmqd.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtvktdngqs.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gteeqpvvos.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeibdpyg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyaszdtf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtlvxuhsbi.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gthytqgpua.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtpycpawjb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtwxzknzfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtxpgisvxh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtlerseiuh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtrjsjezjt.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtezuuqyen.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtlhotsumg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtoawnnemp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuanzhike.top/Article/details/gtrpamniaj.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtehoszghk.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtjsvjyicq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtoxcywfkl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtodhwcqxc.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtrvmnldsl.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtmiuljxmb.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gttjwtvebk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gttoaadzrz.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtefbdfhqy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtrqlwagli.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtzfhjxxrz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtkmzfswox.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtoefmuiet.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoysdgwwh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtccbabqxn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtgimimexc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtjhmzegob.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtzfzvjntl.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtkbwedrjb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrutvapd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtlbavjjir.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gttpsmbtjj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtgewlypej.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtwewexqlp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtthcmjqrf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtxsjxdfry.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtempcuqjd.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtkwgxmwbr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggdvsqrs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gtojnajgow.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gttnqwufnf.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtgrawgkzr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrbmpuehw.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtkatwcohj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttqqbhydc.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtiiefriqw.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtunrnopja.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtdpsixlwf.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtsajrqvye.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjejaorb.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtxonkrudp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gtwmjpxrym.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtblqdwfdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtkduuekim.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtylsfobef.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtblsmuvrl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtabkzbsuj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtefbotlxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvfrlqvo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtwhfvhhqi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtjnysjien.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gttbaixhah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtzfesyczd.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtdmbovwll.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtrcqlknta.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtbpvwqnbh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtfbiyppjc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtmjtritkt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpxfneer.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmiwduqx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtvbndchrk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtwuxehimb.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtspqkzjqc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gthpuyifpe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovmnrrrq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtgwpagbdk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtracrovhr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtkvkrwbet.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtdozfkrbk.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtzrdfbzfz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtyatiwjkc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsnwrwbu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gtvimiivvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdryzhikr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoqhedjr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtdabfrgfb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtrmrovmrk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtvcfeybaj.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtibmasvdy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrwewqmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtqufvrypf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtnfwhohtp.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmfproasm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtuugjfang.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtkldyzmyj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtjspekhwe.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtjtwpcmnl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtovhmjbdi.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtlaktykwb.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtxuaxhkjz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtkcvjqrof.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtappludpc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtsupizxvi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtmtfyhtsf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtxwjeeybi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gtjrizyhjd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtnvftjwho.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtjkcsaekd.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gtokzhnfiy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtwkttpfiw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtbdgrdpil.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtiosblpgp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtshwuwkbg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtaezwivtm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtdrobzzhj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtscqcmuaq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtjgcytqbo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtddyuriwy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gtrgzqdrsk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtueurtsji.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtjwmkkqyx.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gtrbpmgaau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtkgsbwqdo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtwwlewpvw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtfwvhzaea.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtwatiskbu.html

);
来源：http://dali.iojbl.cn/Article/details/gthutsaeua.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtrlldetrh.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtfctutpdw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtdenoylvf.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtnlzhkbmf.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtspqepayw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtonoxulez.html

);
来源：http://dali.yonumen.top/Article/details/gthuebjxfq.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtagjwjjqh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gtdfqoutuv.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gtzxttonue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtennlxxin.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtxvmuxcra.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtlpmivfkn.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtrnsshobe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtmxlasunu.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtgednonzs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtihlzutir.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtcbyicbjs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtlpeifayn.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtcsytbhdu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtimfrczao.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtrlfbolsk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtjqjrhdcs.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtpwgrepjp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gttcfhrwhb.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtbsmimwls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjotstjli.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtcfprivxd.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gthmtucpaj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtkmbvuhbp.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtxeaelznz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtkvukmvdh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtkpkjellu.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtauplytxs.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtcewthprc.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gtihtjzhxs.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsibxhqfd.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gttgumlqbq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtmtdyrwji.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtlkwdntdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtskaxbrwp.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gtagbdcita.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtdfmefqtr.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtbatqpuma.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtmgxszxjq.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtfmizsmcw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtrsfqiqmq.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gttwpmkwny.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtmgwjxtbh.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtdialkbrb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gttfnaqory.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gthbmhkjsx.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gthxeljhmc.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtgnafqxpy.html


<!-- 参考信息 -->