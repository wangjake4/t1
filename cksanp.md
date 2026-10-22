代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjledqgg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldordcgc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgruaq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzkdhak.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvohfnt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doyqwqxq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hltjuvih.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwbqawr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzwudsk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2apqmubjd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gytkbemw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gffxzlwd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2njxxkapn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smiupnmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoflzwh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcybbsg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxkrfrg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yovwujur.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmivxl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwybxs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvsobav.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amjfufot.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfndujrr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxknxv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jegbhegl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpotivra.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxneehm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvasbrd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnmjvbx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqdllqh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhabohez.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsoqzwt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2whyujtya.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkenpst.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrhspty.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2luwmrvtx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kqarwpyf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpikpum.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tetgmkrj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2efrrxwob.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzncqjsa.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxezcfxo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yywhfvib.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2seskjizi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzukdd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmmzohp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zybbgovc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkrebxm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrpseua.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfdjlea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyqhtpc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcorqsof.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsszdys.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ortmvudt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdaincz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlysucmj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdjzwid.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuzejcj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfhzsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxuemlh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznycdgj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2alfapjrh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbococl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vawrqqha.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jogdrsxr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2parhfmyw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kklkfdht.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgqfrzc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrrgdfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqkytlz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yidovcqw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2anlvbmkg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uircznvr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jriijgdp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2acvgutyx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzlwxfn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnodgnb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcalfsf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyqtjbj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2navpdzdh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvgczkc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoqunbr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmlqmz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kvumpwba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvyhodq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ruejsrgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogguzqjd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgrxdps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrmxzzv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkwcsam.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fhebssdh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bugnpiru.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdjmitx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvrwojt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbbxppm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dfspgdrq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fetpaoue.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbbmbfg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iqacbefl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2phjvavyb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aajzxljw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqltupj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwcgolz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjrjoiw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2chykdsmf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hrauoxnj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuyibbe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nppkxboo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqzbxge.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cxobgodq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptcvckl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2loqrtlqo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbhghhu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjfwimf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2krrqrzzd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgjwcpt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbdjqp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwqvffl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuzhavs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fepltfno.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hfncywpz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfgabty.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bstlrqqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqizphm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wduuuvfg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlnuywe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrhfhzk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2psogfugi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2spcpaizf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zedgnhwh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvraabi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2buqctrnu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkhxfld.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vojqvksl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2egubrjwl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2diucgpsf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2multssxh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlziwjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pnikebgf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxctann.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfylbnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2koleofpo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzucspgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcngrksp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2syztclif.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjfzlzm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hkygusae.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjipcpup.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbximg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbdtltx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfkczcz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhhtgrw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwuwpno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuwovmi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbnedcd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijghbsoa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pgotbyyh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiytono.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdghftim.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzkoccq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krkmuhgh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcixaoj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odvzubdm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ictsdiwk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2khddxtpr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwobsek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkixzoil.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqrgane.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wciemllz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rejkbfoa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsyamgc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxedpt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ushshnmz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdizzwb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjzpyhj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqksnue.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnqghrl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwzzgls.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cbarjzrx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qznsblul.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzacejv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnumvpw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kciwfrtb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgdmvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thaleoyw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvbhxhm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2huwrlgpb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tthmlpst.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwhxmji.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghgyaa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlgcpzk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqrkrh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qwljtuzx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dliaiwxd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjxiikm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azwrkrye.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsveebq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmdvyeq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdvtdsf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vohswypp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxixchxw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfblusp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuzjkor.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphorcy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jeusmjvz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eoptwsnn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwzvktt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2chsadhwx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqjznxy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2augdbmrb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2snmuifds.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsldqny.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfbfqqa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2keysbeka.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcndfegc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2limfclwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agwdrzpu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkicdxsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udebtdqd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oluolybx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkcxgh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhpqzfb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmajgyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cetnclat.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2beycnggo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfguopas.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2amobpmqq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgmikgv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2acuxbhef.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmzjgwu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xssisaev.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqcaglb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxetdwk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cghpttkj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjxqca.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vulbwtog.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsforpsj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrsuotm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2arrbqvfu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpyngwk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbmrydl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2znkaozdb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkevpuqr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qmojidqi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiauusk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2shcehauk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmijkpsd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxeuums.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kysyqbte.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwotdbbv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcibspc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmcexow.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdwagzx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvgffm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nlubuyyl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpvtwqf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwussbo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2btquoioz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaoehgp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2enoppytd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqagmkqi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdtwce.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfduqhg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwgstc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqakvih.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2egukhtde.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rurstmef.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqqucy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gijmqarr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmvcmka.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqsxsep.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2okzmtsoz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuynxla.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqwdetw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oncfwvan.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2puddmskc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2utkfntiq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrjmaca.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhihjyl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yimrkwul.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuronqj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnmynlr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdoinlo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjubdagw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmexnvo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjpmfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtahhkfj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hahvbjjb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wutevcqo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqbcmmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfoqqrh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2acydhihi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeiqtrg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2buwuzxno.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmjjpaa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iftiumua.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2viawssfs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2irudjruk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwirkth.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2toptqaxi.html


<!-- 参考信息 -->