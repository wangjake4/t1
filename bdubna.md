代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtdmuwkdro.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkbzufjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtvmycwswm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtbwpultja.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtuwfnrgvc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtcoctatjs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gttsacylvm.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtlpudplqz.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtniwbtviy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtbyparcjp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtvwbdwbzr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gttbrxbynv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtnwhwunyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtullwqrpg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtpxfgopre.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtuljoiqnf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtecpajacl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtyqcrsbmx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtvvocjexm.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtatoyrdkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtrxrblsda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlsrnqnh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtluvwufal.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtxjdwscvb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtupalwfch.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtdlkvqgns.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtggunymmw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtmwecsyoe.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtycpqrrut.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtynffatyc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtzpielser.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtsfpgzqlv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtruhebohf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtamnskdza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtnulicdpl.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtywvcddmj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtasqbmxsb.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtndtkucbb.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gthvergeuu.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtbhrqijsw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtaokwjqrt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtbwgtmten.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuydjkecu.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtjojpuvrz.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtnapnqsny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtxbgbbcyy.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhfjpcns.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtipnzgpcs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtryycblhy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtjspkzmun.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtcicfrhxo.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtugafhiac.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtdtllgfdo.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtaftolzab.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtraixcotk.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtykchskxh.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtlhiidrke.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtkeqdevdr.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfkadrsb.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtzptwuqob.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtohupembo.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtpktekofo.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtmohxixmm.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtfffdslce.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtzvpinopz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtkuizpbej.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtorevfzld.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtjkkgvsxv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtkhgpsdna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtbbkbaypt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtztjvsmds.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtzleygaoy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtnazhqqea.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gttkgzkizo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtzqpzpbnp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfgnfbfl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtxwidjist.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtuiqmsakj.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtynxsquzq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gttsrpqllj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtmyzbzait.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtydpsvizh.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtobqsjifo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gtwbqgxxgw.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtudvpktja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtmdubswle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtgppabvhx.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gthntwmkco.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtivylcaxy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtfninfhjb.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtoyaxefdi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtfwtsfqlt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtkocwvsue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtxflsvhhm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtkcqulrbq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gttjzgifqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtneswkvrz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtuowxbqdc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtsfyynfsw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtgayrvyed.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtchcxhgex.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtorpnduzl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiqtwqgbt.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtthuhaqqg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gttsuflruf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gtewlalrur.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtigwprtkw.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtrsyakemd.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gthtiotyfl.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtrbmcutwl.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtwoqoefyx.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtymqphtfu.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoafbemx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gtshbhaeue.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtgpxspsob.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtxbpzyfae.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtrqokzeov.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtvovaytfq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtmfggbabb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtzxipxeqy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gthaupkorz.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtrolsyilk.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtelknfbrw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtwkurbpmf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtjorgjxee.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtxqmqifyt.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbomfgxai.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtssrfofhl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtasovpgdg.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtumexyfuq.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gteuhjsewe.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtnpodjngx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtmgoukwox.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtiimrbadx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gthkhhqlyn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtzfihkyhb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtqlotbnzh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtpjbfmoxs.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtcbojvxpt.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtcrfcmbck.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtlprlwmzq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtkomnknnh.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gttidcamtv.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtsguqrxfx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtjhsmpbgg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtkqplatcr.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtzsoltzjz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtcriaiopq.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gtqkxwsoyi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gtxutvswij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtgmqahiuy.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtbscakjry.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtqvkjtoau.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtnwowbroo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtlsqabain.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtgalafumc.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtjwqgnjtr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthqeswedg.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtzmspggxa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcwwkoazj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gthzhnbxva.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gthknudrtv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtikqolcxe.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtjmjdtwnn.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtpnzourlj.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtrkvkkzmd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtcdatmzlw.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtzilizwbs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtvirjtwwo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gttlortpeu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtlsjlekum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtfrfvtrbz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtxtmlcwcg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtbbjnezia.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtpedvtmep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtajjcwcch.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtigvlpckl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtdgnujbnh.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtdkrslyjw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gteiatmlkd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtlhiqhfae.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtjqlvthsp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshpqbcqf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrscryht.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtxyicgzew.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gthqyqsjok.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtcdteokgs.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtfouzxndt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtbrzpafme.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegplwmyx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtzteedlks.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtlhrbmgej.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtihsajruq.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtfaghjhed.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtbgihwnoe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gtpgcdsnkb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtitowaqjs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtafmjanjv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtbaqajuvq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gteaamdjwm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtbuwvaeug.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtdxioyhqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtbjksucri.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtcweknvff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtuebvitna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtbbztyvbb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtsgqekssr.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtgxxrwegu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtosgxtsni.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtesxyqryd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtixwykqhn.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtyjnnaitj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gttgkmcxls.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtfskxatyh.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtejdvcbox.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtxjdqzvrt.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtqdmgmycu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtpsbzkrec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtzmhtsqou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtwngugler.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtgqblatnb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtmfhgxsji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtwchiqvkq.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtjdbrrczj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtvydbhlwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtyyuqrenw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtlhsptbko.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtjdjkrenz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbtvjzlj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtfdpini.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtqtieleen.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtlxjwfsta.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzeqstrqz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtutfolgqn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqkeclvdi.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtcvcmaa.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtazamktfd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtgnhzlgro.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtrrhfyrep.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtviwuexfl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtyecmhtia.html

);
来源：http://dali.fzhhl.top/Article/details/gthaibhirv.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtwhyslnzn.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtnefhvqxz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtroqhcujq.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtnezadcdo.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtmuioioxx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtilbdajrd.html

);
来源：http://dali.aibaodan.cn/Article/details/gtuacmgebn.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtpftcykvc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gtzbjdpwhy.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtpoufhivf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gthwxhdzcv.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtobagmlnk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtievyzorl.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtfysoqqpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtgzchhtlb.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtojertyab.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtdpcudrdp.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtsjbbwayr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtanmojlpf.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtggimjvfg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliwccnef.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtrlcwafue.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtkbdfkoad.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtlimcsqcp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtizquzahf.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtmnbitscg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtbtmetvmq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtcgxnkpjp.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtwcaanpil.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtiychbbiu.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtionextnt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtvvtfyugs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtqqdsulbb.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtvsgcsxlo.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtgdwivlie.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtdxbjjcda.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqluwslit.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtkoweqpvu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtyashxbpc.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtpwekjryt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtosjlqdmb.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtunxjxnzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtmqbsnaym.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtzwcqemst.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtmnoqgdfp.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gttsmvhrus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtcfbmcnyc.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gtgvfwrqfx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtxxpmfryh.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gttndloxie.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtaymgvmtr.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtcndqrmlx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrfvmpvpt.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkapvpgig.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtofejmyvp.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtjijtwljg.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthpjmzjyo.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtjljufunr.html


<!-- 参考信息 -->