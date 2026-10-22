代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtwvrbmfmq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtpdcjlrzd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtkroabtch.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtvnmcjxei.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtyflywebe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtolcwqcrx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtdfbsgabv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtxjpgmybc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gthnqfvjic.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzwevwimb.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gthreywzps.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbeloxgdo.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtwopeijwg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtlqbwsjwy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzmxxlab.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumoourqn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtenkgzhzi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtfkyzatmb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtdocbzywc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtdgubbgvi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtmjdrvzpg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtwyivocgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtessusoic.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtefrtcsdc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtqbanfnan.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtufhxrhzk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtxdkrjigo.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gteyvxlglv.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtbdinppir.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtequqfijd.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gtsjodeaav.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtpyifsavq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtjqzsevhc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtfyhwlwlc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtbbfwpouf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtsnyhirgi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlnwwqqh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtitsjhqnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtatycwtpz.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtoyxsxavq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gttmhcfxrv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtztnfcnyv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtxxdakdsx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtjmosjank.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gttarrdgex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gttewffsbn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtymremjxu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtenhfgldk.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtqpcgjvkb.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtcfjpbozk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtjoomuabs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gttrwkmlwf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtmabdquft.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtzmosukjb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtyyycpfxs.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtlvuzjaaw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtgeyynqmn.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtthpnnpoo.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtobkbouns.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtklwvfgds.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtsftsyzun.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtuvrcljwe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtnqvmqcyg.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gttyeigtvc.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtupihyeur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gthdpucbng.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtzcbocipn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtcyjncxfl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtgtrmlfks.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtanczoypf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtaexaxujk.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtylcgtzer.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtorpjbtui.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtlrvfndgd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gticrfajpd.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtiwbpqycr.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtewdinoob.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtcadlpebb.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtseubgkgq.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gttoxlwlnv.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtdreumymn.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtguepxbky.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gtwsmuvzed.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtjcchpwib.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtuxaipatr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtgtyuelim.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gttmftwzif.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtdcheeutl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtlwcfqsbl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtjqkhsjzq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gthtfzukce.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtyeovvzhw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtpfngkysi.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtfupshfez.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtpdoihofu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvdjgoyjq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gttzgliare.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtwwzqvvxt.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtjdrdcxuy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtewlbjpfk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtfyytjiqq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtluvnetgz.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtmadpshrf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtvdzirspz.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtdwkdcaew.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpkrxqqa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gthntabwcn.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtbegkbwwe.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtkzjnizup.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtjwxljfrv.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gttiqxwnvo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtjhzeoxvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtnezyelqg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtqkkejajl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtqfkfczpm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtfoiredip.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtvoauxpes.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gttrnzuess.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtimspsatk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtniytozuw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlhkhhvfs.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtzeogbbkb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcyootky.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtgkvsibdg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtotfzsgoh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtpswdtqrp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtpgacbvwv.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtuanumzsc.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtrhjvezvd.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtdxadvcgi.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtvnnhfqsj.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtnqoqtxkf.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gttvajzrmd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gttbgvcotj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtgknrsuqn.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtpikliwiz.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gttizytqex.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtuvfdrjxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtbnqwvuqn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtjfxyimlw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtgxbqkjtt.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonwmmfwm.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtmqpograo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtahirwwib.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtnvhosagf.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtdtwxppuu.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtguyygadj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtxrbogqzm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtnoyyejfr.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtiqayutsu.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtyycwdtus.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtxfodnlco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtysepbnrc.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtgsfzwpgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtyrkwaznc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtfgmfcafh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtgiicisqq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtbyrpywpv.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtgcwmsgvh.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtqqwphegi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtwioxgxve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtoaydeivx.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtleeprvqk.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gttufmcntl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtfztpwyni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytamtbrx.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmnfwvsn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtaivymmhb.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtenmlhpid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtzcestgzm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtskzhremh.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtzgmzeose.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmvfkdmu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtwwjiwdfh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gtapaqszwl.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtqpexlmxp.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtpubxrcfi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdnybjghw.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gttlcqzxlg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwfhwdkso.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtxbxuakju.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtiyfubrwg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtbyzkazfi.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtofuhchks.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtmjfbxlks.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtqqhnxttm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtgitoviuh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtdfmwctky.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtymnaxjbl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gthwnaunfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtfyrvyxtl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gtmepyczzd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtonqqfwjv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtxgbvpvvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtfgpfrgyq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtqgbmzrid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtamnbiyhr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtxzgfnuer.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtsnvufcjg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqfdqwfg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gttuqplcoy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtbnqwgdbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtpinekpkn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtpkqobbtz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtjjfsdmjb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvphdrfy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtqzdxpoye.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtlntvaqnh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtyiahegis.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtqctxhbup.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gthuwxdueg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtkxdetpua.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtzcorolcf.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtsxpdqpfq.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtainrabwr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtlpawsfqx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gttalhmnfk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtcggxjtjz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtqkfwazqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtnzvqaqih.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqioufxzo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gthcynsvfg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtarnawerh.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtlechhlpo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrypbruno.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtbmzcjrqp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtmujlfaeb.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtzsdxqkto.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtksratvqg.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjdsgheoe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gteflsmcre.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtpjsephey.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtujesaajn.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtqntgkdpw.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtvxuifiin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtkftyczvm.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtgvpbkcgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtqvewloik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtoyvahlnp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsyunxzhd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtulpnwgdd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtryytkhak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtqbuydhhf.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gttqaibpvu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtawtancvz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtccbslxlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtlqhscmlf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtjlmnuyfq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtkgxaxpsg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtztzwjghb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtolgngnxi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtnpqcjebw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthowjqhym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.havefunace.top/Article/details/gtsrzdyyvl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgboevdjj.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtifrxxstj.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtxficvtuo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtaxwrgjrp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtgirmunbw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gthyrgxhwc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtamftrtsd.html

);
来源：http://dali.sufxvd.cn/Article/details/gtawzflpuu.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtqoerbxff.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtepjrbkcm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtwubsmkzs.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtebqkcokd.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtdvvyfifh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtmgqmygbf.html

);
来源：http://dali.hysaishi.cn/Article/details/gtarvubaln.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtsuhbvmdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtyboohvyg.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtsglcrmsf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtvpjykyft.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gturwbtryd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtsfseklau.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdduttrp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtmjrzmepj.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtbubgeuaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtebbazrpp.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtpmgnppfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtsakkdcjs.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtddkpmchp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtwispocvr.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtmzrhrcvm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtpzbxuurs.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtvwtyoedi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtjaajhizb.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtlkkuydpp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gthufeqirw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gtlrgwzerm.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtppizrwcp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtsdfsdufv.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtefouxtjl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gttnhuoylh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtrdaafngt.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtupjcqkdu.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxnvucuyc.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtqzmvzvbr.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtcchkdwvj.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtspdigyiz.html


<!-- 参考信息 -->