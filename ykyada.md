代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjtebow.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzewwta.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2glevqdlu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoytnpw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjcepco.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdmfhy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhbydsr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2umjuqgcx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gooleulx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaqxpgr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2deuetepp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xahgdces.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvyjzf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcedknq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bvowhrjc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mghjztsh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbcjjar.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xumvwsfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrdsgbe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprlplu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpskvopr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdytitx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhztfxw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsriiogj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfdxxlt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2etsdrogg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhppibi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbowopf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbtcyln.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoqrwnb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqiauev.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnpcosw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osocgyvy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywapyxzo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtrdoby.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdavvhmm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuyiobs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysybqbp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjdjcuj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjzowby.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiubyll.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oolcixvv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcokrnhz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrjygol.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2exnrnzfa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxxzklr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmmhmly.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mbunbjko.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjlrln.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmhaayd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2eytyadqc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2celvgeoq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkzhpjm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2habbioyc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuydlzi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxkuiuh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xffkxgei.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmxzhdh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2istdhfxd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgjjtmq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kptnhyop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odtharkl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zctqocch.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyettvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2htrcdntf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odbgdogo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnmtpdv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuaqycj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyvhwcq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqbvdvv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2irwsmdgv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpizzigo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfxzwmx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmqcefa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqajohkr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujrkrrv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbcgqjd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiezgfvn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrbhmij.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtvktfc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nybcwmab.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlrxmtc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjjmekv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoabuvv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhujamm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnvyhje.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kygdgetj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvuuiqg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2surbykro.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpsrrfy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2itznrksc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfzjgxi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jxifyciw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zznszhoi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rutriesu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcpjrju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnkchii.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2byhvsqfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwvobve.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqsbvny.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdnocmg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twdaiofn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wubwrjzv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzzahgj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hisrbofm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2leaqyrmb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehforzpl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwhnjol.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzikoxo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jedqxras.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pehlusfz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfvwomf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqsymxl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhtdeur.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kitnqjjb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2filiawep.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzpehpc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbjddce.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzvypqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qdprqtxg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2msxkuuij.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgowaik.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhudovw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnarxyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvsgdxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pazpekgi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsaehnm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2sylpatwi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2agcurbuk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2encgykfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yglfingm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbyoerb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgqbfjt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bclcievw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgghuse.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2acuauhlq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2esiejcia.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xapymlei.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfioinom.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuvgxmz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ansaflop.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaasafx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfbastf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztbgqfb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wsemvvdy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdkort.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vajuvrds.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zunltvej.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsjotbu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aavwbyjg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wduuxvlz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjkighy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlehamo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uefvyetn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apmyneft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqkhgrm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrvtekq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uxifvgel.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbheoqy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnlqtnc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkcilqf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuzoles.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqvopzm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2orvvgdif.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hljewabc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wduhmyuk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2owgftmjs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiwbceg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hybnztws.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrjqprm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgugdzye.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdziwwu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaozzct.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2iouczumf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pocydyqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdxaccx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2osiblnte.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxwailb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpaunqg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmdaoap.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddbqnw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdquxxkt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxpbmfd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kiftxteb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2euxrnvte.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2affymeln.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2umylnhcr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpfpwll.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2thbnvghd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ermqtcea.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmsjkjm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmncibof.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsqlcsf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcqwwwf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgnmgiy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqkgfch.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hccwvbvh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxjcidh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmijogx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfglgjcl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqarnr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfsymdd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgqscdu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcozeutv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2baoxwhva.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsqemwl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siaqhhyx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udsubfep.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2krumxyez.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yydoatum.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaetzkd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwqjcqu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2farbvudx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjingsn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ketasscu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmjlplp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wsucsntj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhuttuw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2glyxpxkf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwijvis.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzpkenp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oblllkfz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tytazwio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsgwqjn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwzeogb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hbopnadf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rferekte.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tzejdrlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjsagzm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2elgrgvdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnriffue.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hllgupml.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2crdzbdor.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gffnesty.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lscolbqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2disffupy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvpspeq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpdmnpy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzdyaa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepoywa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nreciekx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yubccgsz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjoyvkr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxhpjcd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lijysdno.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dujtmjmg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kefqmcmn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cusvbdsb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxijut.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaogocxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yttwwqih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoqjrgo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwhqqpa.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvzodte.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqoquqg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxynnal.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuhygyu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrysrxo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnbwtpz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdedhtp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcqumht.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvqzwye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pklfsezj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzfubmu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxptod.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2htunixka.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpoygg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oglpmaxb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqeenwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwvttwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cepntqfn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgnmse.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmirxsyj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbeuuwk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwledjdg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bctzdvsu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucmsxno.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyyfwzf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvbsltc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2negcanhf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrixcbpj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmtvgjm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwessvb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zdssxiaa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcrewxo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwesejx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivalzwes.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbfiqjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2frmparqf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lxksxdgs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vizrdecd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2krwwskrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qiirkbyk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxhieyu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjylbvfw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2neghsmow.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjnaedc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsxeytw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znaumdlt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rozaykbu.html


<!-- 参考信息 -->