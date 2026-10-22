代发 wailian999

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiabgvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pystyuwd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlylskpm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2twgxbumd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjyeuur.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxrahj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiflvzr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdapktx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rszrzksy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2avhqgxrt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcysmto.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xglzxmhr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhulnzmr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cohfkrmk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjtpkhc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgymyjds.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buhegglt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2outrneyx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgmlxmj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lncfoucr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yudhyirc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgimcwki.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuchwlr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijdblh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpbxjjs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbiflfz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrsmjrq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2brlkcoai.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwevmaav.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2elgczqyz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrzovxw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqueosme.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcikbyqo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjoqnsb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrvljrh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qifkikqd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnagpbc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sksydpqz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2czbddzgz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bxorhmli.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2keheiejp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnquznw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyfzcxm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkidsvs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2apiyyciz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbppnwz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ettpuroo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbcxgej.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asumzvnx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzrnyrw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pammuppf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyutcbd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iroxvcch.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2astdffcl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lmadizxp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xenahzpn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqujcfya.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bivwmhaq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2osnojkfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eeypdrxf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoemerp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoagchy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkwufcg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uuznzjxz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlcrbze.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxhksks.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikerqwzo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoslmfk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2meopmydz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvzjvcy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyxakjq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2faxjwope.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvberbu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiztasu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtemgnr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhdegqu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjdffuw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2spddgroz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oderwhns.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvzpqhm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2adfzybnf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkxapvj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkbostk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiqpxsv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qriesfjl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsxhbcm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2drjvfocl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2halnugkv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqhwbrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwdtwuj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyrsxvz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqxtxej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhydjffh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsruecu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjimnn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzfwajq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvbfduq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2prdhbzjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2igwjpkkn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmgghpz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bunquxuk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pekffole.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxfbhkv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgeihwp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhluazo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxswxgxw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjxoyyp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmrntac.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsnxauc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsfaviq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xexufigq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvrdixj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdngdgz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqdsvuq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcidscn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwopwfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfhnmqk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fhecpnsv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvicdok.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnvgdru.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bisjqeap.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yinyqiss.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2miusqrfs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwohoaof.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrcyajq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzrixno.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mngkpiuu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfkpejv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qcptxqit.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlnhfmp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksellsnd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlpweyw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzxyfvs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2txdhjchv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iriddspu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupyvksq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kptzqevk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdyupky.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhhbclj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kggjtlul.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcqqnr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnqxmgs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfddwsc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aifhsvvq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaocsvx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcmtnwk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrnwybf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2avetrcbp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgcmqyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpdnbvy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fepgyofd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgujyrun.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnwwivw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgogwef.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzubcsr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdnsuzj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmbduzc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hljvyrhr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2flwnbszn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbqkdax.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2poeopyiq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzfhrub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrtdzzv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gztuhdxn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhicfdb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgocrdeq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaknpwqb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxthsoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcddxqdm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyehlvd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtovagnp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pthaqlob.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyhvmbg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxccznqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zddswghi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxilzdqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhcxmev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lozbkveu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgwjbei.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bchmrwpm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjfinmz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lheatiuc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2adncqtwv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmzwpzr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxfcelf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqgtsdr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzgydmf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrnloui.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ojewffoh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2augrqhel.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oxomrspk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gedptenf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2geqqzdxk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vabamjzu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vysbpyph.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgopzih.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jlscmppz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nplqjdpy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kavkewtr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dczwpkuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hpporvnv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvccszb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwksuslq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhvayxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbafyibx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsrimvr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvajohe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dutuczqv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2whqdipzc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbcxti.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phxljuhr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwopslj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcynzye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2awivhsix.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wzitcrzf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvirmmc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjszvzx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snttfbdm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zcufkmbu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggryga.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2skzfzffp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2agttgjxz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2eazsidrq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xnenahhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrlgzyk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrcszcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyvqscu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yahxkvsx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgokdgt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcetvthb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbhznmo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtocepl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcrfkbo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2puvthiza.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vemlvwoo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnpcjlr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2izihhykv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hwswghuz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvrucnv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndvnsmi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjxcthy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2futfjqcd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhrnpf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kopffzpr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oftsuuzy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqqrqdd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvsdtqe.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiemzjoh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmhpjel.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zarybjsk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yajginyv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfzsndh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrawlli.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhdkvfu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wznpnzcv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjyqrun.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjlnzpo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2feqomiaj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nslgyvca.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2djtqtimr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfegddhu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2obheunue.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qreaxqze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkmzmsn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2abksfhjs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhtotve.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2acjywwmm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xueqtygn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsxjupy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hurcobig.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgxxpzs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxanaua.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaawpcef.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfysxyv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfnnjou.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbslxrd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmtackp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2slnainbu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffceaezy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlaxmhp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmippzs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2afyrgnoj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqjqcos.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ioghkbre.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqggqsfs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yazvbrch.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oirsxhvp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kznzhsgg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsgsany.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpayskl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynsvjqq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfudfff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkprbbnj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbspsgr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqydpget.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnonugz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmpbmyc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2crrqitsy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawqlqge.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmtompw.html


<!-- 参考信息 -->