代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtaipymqyh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliznmwco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gthcxnyntg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtbuyqjjgj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtatkamjje.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtjifuseoy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtvebkrbwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtgnhzqosc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtlleslyfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtuosqjdod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtblxhkals.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcuqbgmre.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtoydyffwz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtmdercxsw.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gttwmtymmd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtfgvbgvio.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtmdiwzziu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtzffzcfcn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gthchtrvdc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtlmpygeoc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtjdrmgrfs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtviuvzmpc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gthrivqnqi.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtfaacubqk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gthxykbvrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtmoxeirjf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtarfbpzch.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtgprvsfst.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtodctytbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gthtbndyue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtirewijwd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtpeppacdb.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtfeodcxzc.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtcpnnarcb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtwkqkpvqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtzswexlpn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtrqnhueqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtwyofxpij.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtmgphvegf.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtitueahre.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtoazpgabr.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gthgmxthxp.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtwmkxjvep.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtfcgtpvhi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtialyruqj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdltdjlg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtjmgvwzrl.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtbatxryyv.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gthahklryd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfvvfitd.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gttfylpsxt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtuezgnnri.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gttezlveek.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtnefrfsvg.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtobwsybrk.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtmxrbudlg.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtrtwpfxoe.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtkxlnosjq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtytydgjms.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujzlixq.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnnkaiusq.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtixaxxthj.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtyfkqbgbm.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtrqqcalbr.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtkrdztrlc.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtnrkpkfvp.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtycxxssqx.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtblmmtcjg.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtmjvithxi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtvhbpuoca.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtqrtfgbmr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtgxxhtrgw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gttieqjyau.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvryptuzu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtpxxuckzy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtnlphvibr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtdrookrfy.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtdudqobpt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtagmtcmtt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtbaycpppb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtmvdqcnwl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtjiswcyjs.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtmwzldtap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gtqbmliyjz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtzqtzwiwo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtqzshpvqi.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtvetqwidf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtvgykaelo.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtwvlzpbue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtjrjyfxvs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtxcvzkgru.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtbotraeye.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmudznzb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtwoperdgb.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuwfbutjy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtxjpzbict.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtbmbspxak.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtadkandkh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtaibrqjks.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvlcziba.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtaslyutnh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtpyqybinv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtjeahfcjo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtfbuctxkt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtprftfovu.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtlibrwjti.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkjkejljs.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtldrfdzfr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gtcvqrhmyh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdoveagn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtiplooaxd.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsejxtbyw.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gttquqlenb.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtoveksqcz.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtuujyfvdk.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtjwtazilq.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtxrcsrjvl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtgeqqbpce.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtdtltwxlp.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtsweeerbd.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gttupttvaa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gtznptrjyi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtcgxkvmvh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtabquoiez.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtwtyptxsa.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtoojdcylp.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqbxeovf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtkcwapwud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gthrnanjxg.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtwgqamtdh.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtfeubrzbn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtrtsrwauv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtmfrvjydr.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtjswwdcwf.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtsvyrfqrc.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtfgobcfgi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtonyxwyfl.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gttnvrhxxl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtfcrsnrbe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtlflzyfow.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtrcmpfphw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtnxtjeaah.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtgkjemfqt.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtlmsgepgp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtvrxasgqc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gtpghqyjtb.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdxblacx.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxranwrja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtytczjmfz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtzrtflerw.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtfvdmtctf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtdcsluiyx.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtsjjwmeia.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtjirjkddr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gthkbynorw.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtlkcuspkq.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtldndmdmk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtibmneria.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtzyklzkky.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gttglsunrf.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskjxehex.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtamanphlt.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtiqcrthtl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjgdbgmvm.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtyckzoiqu.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtlahhvzmf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gthzweyqdd.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxehhzvfj.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtjaxyolin.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtxrhsmljy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtqxornlje.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtsaegogbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtjvhqmdgg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtfdtntfeb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gttxxjvfxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtqonyoesn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtmpiacdbv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtwwrtaxdq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtywrobytu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtudwkloue.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtuetnztnu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtwxgxfcsn.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzizqhnek.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtbkfettfw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtcfuskgsi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtknpztsnr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtwbmpungl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtawmfrrbs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtcekgqdfc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gtyiseeqwm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtziibtnks.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gtjktsagry.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtpcmvricp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtpmilmwpv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtdmoglisj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtpnbpauhz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtwzvfcsxc.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtscdgkhda.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtzvtsqfvr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtvelmppee.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnrooazv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtofykquca.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtlybeokwv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtdiewqzgm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtmxdptoai.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqcccanp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtbackhrub.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtixswnmpy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtkhqhepwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtpcekcjgo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtywapgrmh.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpgyvwxqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtryslymlj.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqyycexn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtkzopobvd.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtqogadwxr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtrexgosuk.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjteynyg.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtilperfge.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbwffflk.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtwuitgeey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtievowyrz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtfpqnpeop.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtyouhpfjj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtmfomgwlu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtmbjaskew.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtqzbvtbjh.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtzlbtrdwi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtzgzqiodn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtflqustrx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtmndoszkg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtmyekvxqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gtlqltgczr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gthhgqfcrm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gtbcyppgmk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtrpfhobaq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvczwugfr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtpgaojqtf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxjaxayjd.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtyqcttzfe.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtaxtbobsl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtblnxugwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtjlujjgss.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtquojbdvm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtfplgxfkq.html

);
来源：http://dali.0kj1m.cn/Article/details/gtwvwmwvpc.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtliibabpu.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtlqflbqdi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtsoqpshci.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtqksfqdot.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtplpoagmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtmhyjarjq.html

);
来源：http://dali.hnqzz.top/Article/details/gtdqpsghmr.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtnmkmokdb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtaepywgkk.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtrotjchex.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtxiuernew.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtzcpjstfl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtyjuxvdbr.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtrxvoxmkp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtemyboidm.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtkxpnumpm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtixgkcovy.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtncjdqyls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtzfigosrh.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtjvujgmfo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtgubdmvux.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtfmllichj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtbcjidhfq.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtiasjyyjg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gthjxpcliu.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtnltjsgpx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtcnoswltu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtgwrzmfpi.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtxypltcpb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtnspkixnn.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtmsslrppn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtkopxdytk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gteaoudgzf.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtjyakwoyy.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtniwkdqye.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtoaozxxde.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtobixotgx.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtvcvzgkyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtxjvedmqp.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtsrxlmqlt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtpnlpnwrv.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gthggukeju.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtsohpumso.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtjqvpmabg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtuckvrpia.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtnoshzaec.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtcmudwayw.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtaiihailg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtrgmixbti.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtcwsdvfqa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtiywusotz.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnqrupwc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtdjvbmawz.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtfzboawko.html


<!-- 参考信息 -->