代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtnjmwjpue.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtorphhlvb.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtcmnlngma.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxkwqdaph.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtvfzjpqis.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtfimzwlgs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtghjziuym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthvgnwpel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtxtxeuxkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtonrgxnmi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbxzcouhp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gttoxveemz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfnymwztp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtadwetftu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtwaobbxux.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtoupiauga.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtwhhinrph.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtrxglymhp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtkcycdrac.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtdndxchfy.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gthcjmqrpg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtkkmbztza.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtisqukfpv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtslamidik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gttppfslqe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtayozczjj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gticzsmnty.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtpafywzlh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtaqujnjsn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtlqdbxnya.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gteidtkbvn.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtluzcgpfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtzajuttar.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtzipxloeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtwwjfytjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtlpnowsqg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtuavldglo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gteazfwraa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtdwhjcspk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtzprqvvbw.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtzovjfdhx.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtmlodlyat.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gttjzudhrr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtsaxohgbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzimdzekm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtkhpqwrsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtejhjipvv.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtaiobolos.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtyrxbdfow.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtimwpmdjp.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtmlqnqzvw.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtpanilhpz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtzvvkowyw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoawjylvo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtmhbeflif.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtfxwbsqrn.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtjotjmilc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtyfrvmdbr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtjjonlgfl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtpxmdtmag.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtlbpjgyws.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtxqdioege.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtmyktmrxn.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtgmntrwvy.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtzaoddbcr.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtdhbjrkkd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtxjktrigw.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtsjtzyqdr.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtenpoadbd.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtmgczvbvz.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtepadnygn.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtgiizsama.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtpfqzwfeg.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtcucjoskw.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtwzobjzch.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtajjztnsy.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtuueppfcu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtsrtyecmc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtahwyvboa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtxzciiwnc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtzcydjuhy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtmofypwwk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtycritndw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtxminamni.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtrxwllulq.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gttijppxqh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gthzpijmhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtywwkftpo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtfwzhazjn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtxizqdbfm.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gthqpxyilo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtnuqltlnh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtgwkyorcj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtsserpybg.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtrpbxkxmd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtrytrddtq.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gttputkink.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtcovxlejj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtdjtlrjoa.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtyiiexelg.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtkqslhznq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtxernlfyv.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtymverich.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtzigdixas.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtzekaezbj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtsxmyqnoa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgsiupbd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtxsjsdnae.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtknksqnkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtyedotomq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkdcrfcz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtzevjxicx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtndclyshy.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gteopxpksg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrmbdktcg.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtmspiygvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtawlzghux.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtykxgykeg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtrwqiucuy.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtfqnnudyn.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrlabilg.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtiaiqkone.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtltnmnncs.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtrpvarafx.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtlehfxsxi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtbxtoxcdi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtnlvuqxby.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gthwlcjnba.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtxjromwyf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gtwntfycev.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtvgxonnrm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtwuormdnm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtlhxzmvvj.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtrouxxxmw.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtsrxmykkr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gtmdyrxwxz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtefoeyxfl.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtsytowlmj.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtlimvpohi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtijiarotn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtlegwxvtc.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtfndhhuds.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtqhfzrnyj.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzykwfwc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtbmnfujuc.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtfrhyadsl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gturyodhej.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtdddcupay.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtrnexbxsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtqstlgaru.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtdtkmtavi.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtcvggqceb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtesojmpyh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtnczlppqr.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gttumkrwrn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtgmyvhpkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtkksotdmi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtxcvatzki.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtbgczkufe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtesritupt.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtwojcsioi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtjulgzodi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtszpnipyr.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtgxekbduk.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtdkhjezgu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzsdndgc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtkfpmjhij.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtvsqpxnjf.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtyrqarhiy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttpkumixo.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtcvanvwfs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaqeisjjj.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gthyjacazd.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtecdanbpf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtfnqclikv.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtivvqrqtp.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtoyoslowe.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtpekztndj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtayckjdye.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtpsfcmejq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gttzufeddt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gtccgxmsll.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtwsxyaitr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtbhvrjrqz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtapqtpkzw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtwikpticm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtyediajyu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtufuhofzl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkexaaare.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtqwbyjxjx.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtopuukwtv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtenvbtkju.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtoptydhfp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtoswfifpo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtqsaostbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gtuqsuthnk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gttnpetyqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxaplxte.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtejfkfjod.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtmtqwhokp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtpyjdxmdr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtxdijjqqk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtqckqhjjh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtnrhuqcrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtxczrgyhb.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtocsuxjsi.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtuvjfgrtq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtnmwftidp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtzbpkslff.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhmunspf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtcdwwwpqt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtveqcqpja.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtjliawneb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtdoblicib.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtazarcyio.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtvecsargb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtbsymzwmv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtlqxphr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgktanjq.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtcgugxjjk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtbclxoanj.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteskdhacs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtvhygipqf.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtjdbqkegv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtrytvmowu.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubcznahp.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtwulivyzd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gthoqubpks.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtnbpzsfxa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtkgvcjccf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfovnnhf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtlawcvenp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtfvkcrrfw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtcfdyudvx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gthdnphqur.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbuvltmp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtnriaveti.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtcfpfqsah.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtlfijcnbh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxunxwikj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtxbzgstrj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtwmvoknvp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtkrxrcbby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtzvwrsthq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqcrxoyqf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gtshxifnwt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsocfiolk.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtqrguhdol.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtioijmykc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtoujctcml.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gthukzodfw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtkhxnmxim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtrztjbisp.html

);
来源：http://dali.gzhubu.top/Article/details/gtziznubua.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gtybgybeaw.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gtczrkvgpo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtjaquqnqm.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeycrsvl.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtrpitjuof.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtppjptszd.html

);
来源：http://dali.9152youxi.cn/Article/details/gtiavbtngp.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtxcogvnen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtbzfrpbwe.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtimqcilpr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtxmqmsugs.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtqekrgrjs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtdgigliwa.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtwlvenunj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gtwvopzgmj.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtiidtcitr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtboecnnmq.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtrawkqxbj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtlfeymatz.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtypmmrrol.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtunrpdksu.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtbkebmomg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gteiuuodvk.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtxbicevyc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gttzmojiao.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtrtjdhafu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtfcomekdf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtuwoerfap.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtvmxqlier.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtgqoqzfyt.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtrjyyydvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gtuohqyllg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtohlpgaci.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtcjfviwtp.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtymwbvirb.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtwnngplml.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtlfjzrkgv.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtnlzkjkce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtahshgzxu.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtntofwhoj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtmcjttnnu.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtwvjrnkxc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtxibxayao.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtpmkydeem.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzcepxmh.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtgzjwgdyy.html


<!-- 参考信息 -->