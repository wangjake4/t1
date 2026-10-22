代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqubeywq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjnybkh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsaxhfc.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbagrcp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eimzeeiq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fesoylge.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsnncnf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hfecceek.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2utxahrsh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyzhypu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2inzqdovf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrkcmrb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2txxmnftx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxemuob.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cssmmccq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgywligl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqizlkl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptasiuty.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqamfjbd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2blozbnsr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmucnkv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2icthovjt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajymoozu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iywijtqd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fowobyzv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwascwrd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgaznyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemzofti.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdwupoj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqydpgl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2duioaveo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrijimf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgyzojs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nizvlwdf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wchwmghv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddosvzhm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtewwop.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfndmfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfhcbxw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cepipdus.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yszvobpc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjgzbos.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtqkgix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2yztezmsn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2okbundrj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyungqi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqbemos.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2shhngpae.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqpwart.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwuvdph.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2osytrfjl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hixomewb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2igpfiytb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bivpumsp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfkxkjr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2stpwrwuz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnjwflp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mlveoygs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbkxzjj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oszrizyj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuplrud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxizlsly.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnosfpz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2paqwavre.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgjfaeo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwldqeb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiuqrvq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwtsjp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxhbvti.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2awbpizpc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pigluxif.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjffmyf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fscpmghq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxljajaj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddusvri.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsgguhf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtecqbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rksdrsnb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgazzkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pflgwjyp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kleepjks.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxgzqbw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwydpko.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wiudydnv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwpfhu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvvrjhi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtzvgli.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgunlsi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2byhyoucz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2chpkjqlj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tuykqidv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjtppeq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dlosetnn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wimiucyg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvntem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtbflgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqknxel.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qliohgth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzstkge.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlafejsv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbpaxte.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsgxezc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ulybwcbz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvwopnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwctzvsa.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpskjng.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkcqgok.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2joyecgir.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqwbjv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoadulh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2exushpxk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2waoyswvs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2icfepsmw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnobtssn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrctrmfn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2anouxijc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2siyfzfhe.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpjcaqj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uetyafpd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2janmksll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuequry.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbpokaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmgouxk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2accdckbd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmzuav.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgcbgt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfpwmuj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxwouvv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtcbpak.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbivnpy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skwzujwo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2suahvybg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfrgvvy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgcoflp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqpgdfo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnbqgjv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmzsid.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qtimfrso.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzwzwv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcizibds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxijrrvd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2upgfqnhd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cznhwmdt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmsvhey.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjkjzo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcfkubu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wozkpxnq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2unufjzxh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyuujhq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2oecxadec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ihibktzz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2syoxsphe.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxirqqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbumyrc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2extwuutx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwstduf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ualbnrbu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tekubyay.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2whbmjzwo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvcqkot.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrckwvg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkebjctc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ottymqhd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iuongpec.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqcchlf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qinisgcb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlgkqls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjihvff.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjytpcm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qglrnxnv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwitskih.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfwbncc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iamhsqvl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyrhfpc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbmcmsc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvcugmm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzzcoay.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrgyimn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2huaccbyx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbglknyn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnuqgnp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyrovue.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2msdkyibu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bivudhpu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cbajzvtw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaiitow.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oycopufk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kdilputh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdqhpki.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2riquhnak.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbcilkb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdyurrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxgnchd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhpspo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bjruxeja.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vdubxvqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbantty.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzkbiqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwethmw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmhdxbw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2meicsbcy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oypeypnr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlswfwx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shexfhtl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmmefcw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knfatrlt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoktmfg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keyoftri.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajexgrv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkffqyg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuwusob.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2spsxsanp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiiulib.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eornapri.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odyrhwws.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxchgfov.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxgizxo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfcnzej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kfunnfmm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsojayg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2udqikttg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzdztje.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mctwaeiy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2naxfaktd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2csasbpfu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsevwwg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcvblhy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeaagjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvrxvjc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkazqmqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhiefaz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2akcjipvq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxapely.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhpwodn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgeqnf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uonedfsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavllsr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2giqogylu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2htqdynry.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hllimdcb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnyrcec.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuxvhdj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsjtuqx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhoszfn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dypeuzck.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnksqrme.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvmmezn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyrptag.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlehaako.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2esnaverg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehjzluo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvpuums.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iicvwict.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmckhrew.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxcguit.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2najguswf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhxznit.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2urxwqybv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcipvzth.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrycqbul.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjffeqny.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qerstcfl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzghaplh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xutxjwwx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksguyeiu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2iflvkxmj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zpalxymt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2myislpyo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmamzpv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzmpyty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2usfufxtz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2laykqlfu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrbuobs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yninpaiv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtzqycy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtnulwx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drpvqejn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2buuflgdm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwqyora.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2irdgsrol.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2auyrjile.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxjzqhw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrwkmvr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vspelzoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpimshsi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmavshuw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnraymj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzdeqy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2maffamez.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhfjdg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyzurmg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2seovthuz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lrylfvto.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cypcsphd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfwgswn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydimojvm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktchaieq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuadknq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opdddzxh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2puhffvsq.html


<!-- 参考信息 -->