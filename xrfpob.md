代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtcqcbxtkl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtjvlnhuqv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gthszyffnp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtmnczovlz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtyncpeaob.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfiwntwhm.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtgvtapbbo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqruajjeu.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtwogtnwzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnivqucnk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtzfmnleok.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtvoejhbgf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtwlhadxlr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtlvadhhvv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtnxhseims.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtvhmcjqgk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtiujqnfco.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtgnvxskfn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtscxudnmy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtjnoblyyy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtguzpuyye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtjqqsxxnv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtdhxjfjpl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtndwnewxx.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtaiqlkjlo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gticxsqbvm.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtaftuvbkm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtdsbgsdaw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzhmahvv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtsfakmlmb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gttnrhiqcg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbpgfugu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtlhdtxlgr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtuzcpzllj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtqqragvjj.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtgdcymppe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtcnstgvha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gttcudyuaa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtyikbydsb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtmtjilgxe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtrxglxrad.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtrcpzrnbk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtqedbikcj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtaevgwnoz.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtntghfxkn.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtyfyynuto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtxhkntzrn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gthtkfkgfc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtwlygawzl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtdmhltyce.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gttzjcbwgg.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtmeaawuaa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbucydjx.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtuwxxubee.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtvqskdidh.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtdgagslxt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtrocysolv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtbruwmilr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtncufzkvh.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gtunephzaq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gttgcphbxd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtqrjajtgz.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtehfzedcb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtsxtjfqet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtubyryhyk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtvmprsdud.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtyogirsll.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtofrzztoy.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtfzcbmkvz.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtlqxczogt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gteqjtbhnm.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtaydgbfax.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjkajhwan.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtgryolxgk.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtreyhcytq.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gthalzfzyg.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtunklspyn.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtqxtocgvm.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gteexcyimq.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtogleuxiy.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtgqnmupeo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtwhowhwcw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtgcivuxab.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtduzlhzmg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gttawlbwyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtbgrxqvqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gthcbscjtu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtvdmbexym.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtckqsumbr.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtecnwqbnh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtrabltofy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdzvwwvt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtpmfivvas.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtkhitvlyo.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtucopkape.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtqdbgpbkm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivhhicql.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtxgbeiemw.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtwbmrqsgy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtmfqgqtcr.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtlmdnjuda.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtitayudny.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gttqjidwdo.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdylfqacq.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtzprlnnds.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gttxsjbeto.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtwziqexww.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtbwykmrjm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtefdbxuqz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtjbvfbjwz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtimhukfer.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtdriofvrr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtvjfvmkaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtylyxqnum.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtuuikxydf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtrsbvkvhy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvzbdillo.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtwbckwgwr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnrzzahkb.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtufckuqyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtkdxgvcvz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtjpzbeohc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtsxtifbjc.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtmukalafb.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtozzvgdop.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gttexxrrcq.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtdujksckw.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntivvwyw.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtarxbwgxa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtpplzfqca.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtarujxmhg.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtkriahcrg.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtxohlwuwg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtltttcmba.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtetbjolpy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtqyrqdmlh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtogzphvfd.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtllvxizds.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtjtuqridt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtlemexhlp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtdlhyrxsd.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtlbsooysa.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtzjibmwbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gttmnmvgfs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtmdsvdals.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtoljspnwc.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gtejdchcrp.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtsjzpsvyl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtqcxepivt.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkccnfzdt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtbxyusgwk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtnjllsczp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtucuxmkfw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtaqrsbtlu.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtgzgxnraz.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtkkabtsmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpihzvriq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtkkmskave.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtnkdiccjs.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtpqpxbxmg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtorwkbcpl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtifnzitdr.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtvfiuhibm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gttnlxxqyl.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtmgrepvta.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtsijaumzo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtyatdiznv.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtrqtkfzvx.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtgqahbdvo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfakkblfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtikcwtpxq.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtulzlirap.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukbnrdgu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzxooijxl.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gteoirjglu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgvxtmmtd.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtcqnsduzh.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtwxzxwubp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxrtapoz.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtaohtjeyr.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtovhmejaw.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtcmkokgpg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gtylvkkfoh.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtkyflzmfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtsxhpxgpk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtfvdoozbu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtagzkszls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtmshcxqwj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtbpkwnlwm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtotgcilch.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtpdayejjf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtbbjjzdqc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtvvccbvog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtndambsce.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gthzxcuaeh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gttiumsufd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtegsbcuci.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtttbuwxiz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtjjfztquw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtlbbkqyaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtrwhdjahc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtiwtbcrtq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtmcstelgh.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtaqhlvlqb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtnwfucqvk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtxpurxwlv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtgfyddmor.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gthbrsrzuy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtguaictsg.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtqhguxoms.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtwfvscgkt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtmfazsftl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtfkxkzujk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtgdnwtkjx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gticgicakh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtwwqjfdin.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtzvqhatxv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtqegltbjd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gthttugyha.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtumomceuf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtgvlvidai.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtxrpqpnos.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtqbljhhsz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlflkhill.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtchgvipdb.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtwpcpzatg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtmlwpwfnu.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gturdceglb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gteigpoqeu.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtbadzysce.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtvldgtmzh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtxvhyabqv.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtjnhifurc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnuiyllx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtizwokhkb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtypusegdr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtzowtwfod.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtplgmxoru.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtmeyprwlm.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtgdxqxazv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyjmieym.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gttyitcxsq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtroijqzqe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtpdkapadu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtvtgeiciw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gthllzsbco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtqhbsacqz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gthbxohvgj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgiapapkx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtmydmsmhq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyxywzgyn.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtocpmmpfh.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gttrkfsdtz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtyqbwyapv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwepdaoy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtzzgtbxyo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtdxalpyuv.html

);
来源：http://dali.aizwys.cn/Article/details/gtyrsxvodn.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtytzkpdkw.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtnazbtder.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtfnoojczr.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtyybtwepr.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtjrvvlyed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtukucxico.html

);
来源：http://dali.aibaodan.cn/Article/details/gtqictxqkt.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtbbwicjyr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtzxgkmxbc.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtfmbukrai.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtwwzjwwxa.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtlajqxbyf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtiddejvuh.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpbdhlhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtejqtchan.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtndnznfkb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gtyerzchhx.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtecxeskfo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtczbuepyf.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtsmyhcdww.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtdhyvolgb.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasyequjc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtbscxaixn.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtfuvlbmbz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtnmxotoem.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gtdxiffyfo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtueefzwwf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtyhdtggdm.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtyuxlkwsa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtbzhiojwu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gtfsobtajk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtyuetdeuh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtexzavixw.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtsfgcdjwp.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtysbchuqa.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtlokelzln.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwivkqboa.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gttuowevxw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gtgdwmwlwi.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtujlurbsm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtkflejtqe.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtyqhlaggr.html


<!-- 参考信息 -->