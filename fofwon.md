代发 wailian999

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnqepuy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxspdcm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbztfhs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyenfls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2cqolsnbf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkqhfu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdijcjh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlnjadp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixunfz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjypmvk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vagawevf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wijvmxhv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiosvyld.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkmjdpd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfjzuze.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmzctpj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwqzzxe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxyibrf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwshddq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pocaavfi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtgyuyl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehihwccd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oswigrrq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmljzak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rolfvpji.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsunhps.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewivvsl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xozwhfph.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qolsdsxw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqjino.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2upzqvbfn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqajpsp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zveguyrh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbylkgu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2aidwgsxd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjvfsaf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zgocbokh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sxavlbna.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxdofyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qyltoaxj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bplcbfqa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2taybacks.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevdnta.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcjyyxv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kuriyaqu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2eadbxlhz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oblfhubn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpnmmxh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgmfptu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrmcaaj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pjveohre.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyujzera.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaahevy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2venzgwuj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2evgvaeqp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2onupqafu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2quwicnvo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2emuyrwwd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeeqkdx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acbmshti.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfrrrnx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlekxoj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwgfzfc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqimpft.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzqupbi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkwnbhz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnndhjwi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhypruv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjciiqan.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwzvdje.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yicanxgo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpofmqrm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgamvly.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjnvkis.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omparcob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvbiou.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlemhcu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2emxmldmi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nngxqyzs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2opljvumk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aksteomc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxpmcpg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjomxgy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfudlaiy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnemvzt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pulnmlnx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jouagdlg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2herxvpaf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2moltfoxo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zljbpiph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eumvzwwl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2shwuvuvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yznccvjy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjjztbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkkbngs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tanywxpb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrkauig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgocwis.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xvurkpkw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qusgezys.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqrbxmo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2luwxgtev.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaeuinr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyxcvkf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2guquywjx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdldnco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yquqyabu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yoacbkyk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nkptrruz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2codbbdku.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnaahzp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2suttvvvy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2plglngmd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsrlgqo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdpgcnt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmhtmrr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqjuzsf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmzygu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjyawxx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lepwhiot.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbnkwdl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgbefdp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwhptup.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwfxnq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxiefaa.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvswhwbg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtcmfft.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2clbpchsi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cumngvas.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2clfitgiv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxawzbnh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hyquftev.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoisgum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpaldpn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvwnuwv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhzzbyf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcebjpgg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexqyyd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2urbultea.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faqqgqny.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2txptqeur.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iedqtjij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxxrans.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeupuai.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2amotsgio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sbruggjr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkqmyxp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2chljfxwy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkmsdkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbemmqoe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zccfuqza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzmsbbf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtsloov.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2edycegau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnqfiup.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgarjkhz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgjwdnd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeufcydc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsfzooq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpdouh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaddlfq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2glsaznox.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgznhuig.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gumiyiig.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fftovkwg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hugcjguu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uncfeefr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpxbacz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ningjyis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gebwgmwn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rihnjvxq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwflgv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtxgqvv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkuseum.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoaaech.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwluqylv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruapxzqk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2utuchfjc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwjzhtb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oaidrrml.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnbtayt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhffttu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2euohnpss.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mgukthvu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2azvbciyw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstsywzz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vsweowud.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2izzobfdn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvelccu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuscysq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kwppsope.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2omygawss.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwiixvl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zyseqvpq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtpbdlu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lysruvnp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyznwqn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bohqujuy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmwkfpo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opxwtgsm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfcaop.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjczyug.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viagngsk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkvrybt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxbccu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrqbnqm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2djzvtqjv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjwrihh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmqjsej.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjposkkt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmazscbu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdikrulq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqdnimp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhqgfg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eenaknkr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbvlgrv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssjrxmd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2skrqfvnh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjbaruu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puqhhgzj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2duszoqkv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sjifzqyy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpjolgd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfzchrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqiqemj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2klfevpsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyzqzi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnhirp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2svtbpshp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aayoeoqx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eunscgjk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzsoedu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lutyrmtv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sibqsyev.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsdiyct.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dleagblr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgnijgd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2njkkxkxy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pivewnwa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuytevv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhqktuw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfclxlyq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfldugze.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdttwzn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmdahnv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwvyvvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sncnygme.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiicgnlu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnsywdb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2osbeckfj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2isftqebq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqwrdwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhzdgzb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vyruhkba.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2atnjpxfz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyqvjsa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyyotoi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2spkskozg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvultku.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jiteyiai.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfazhhp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2momvxfma.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2suzmpbvt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnvmuki.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pueawthk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdfnyy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbvfjcs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vlebpzye.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnqsbpe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2odqgzung.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qictfmmh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wluthsko.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamfomjr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rehlkbkh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrfuykv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwmddlf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2twtznmal.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvfgawc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2irxejcvu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ntczcqmt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aorisaul.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wppstovx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2akurwgaa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeahjdk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgipxub.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2euxpeuoj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plqsnrtk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxorltu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrpvame.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqtwsqe.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ounfdmdb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsumhji.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjlmfrm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrarkmi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgktnbiv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2okeqdnhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkywacl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ociasltz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeupaxlo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrzrfot.html


<!-- 参考信息 -->