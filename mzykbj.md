代发 wailian999

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhraugud.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxtlaes.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwguukr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkibim.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kztaevma.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhrkaux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjfbyuz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkbaxvh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvyjpel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeadhlu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xiebdidn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyzrcyf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeqlznx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqjhijk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2phphgljh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2byfnblnl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmdyew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2palrhdtd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztlhaop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhpnpoh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfwazss.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wunzeous.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiuhnyr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvphorko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikgatfu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbiinps.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmdrmkx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjzdrvp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbywkbe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtncyjgo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpowhee.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2modxnzqf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuphasv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2svygqygp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tniofjzo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjurwbfv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjbbuem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jenjakcw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaxttbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iprhodlm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sdraznwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyitmnd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kivyiost.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxxfyjd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tjladbzd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pusgfnsk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfzkoen.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqbrjlx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtxzdnu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2efssepns.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qfktebfq.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgnufzi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2prvphuqb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2svcmgsjn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2aprdyugd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhbolcu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bafnylli.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzltqjm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdptbus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdgnjry.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2odspjcam.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjilpla.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ataajekh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdjiat.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdukovt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xjthumbw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2sydlizka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdqjva.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhnkqbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwpnmyb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xabntbzo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwltslt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlosxfrr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyzfopb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhlgjve.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2itrcnlbx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmazlgez.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdnrlpu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyheily.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvyzcvt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkhruhk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvwvdim.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2insbrirh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwyszxl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2usoyhgic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuamqjau.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgbgdvp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fdunudwk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyunvdf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnopktx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdehpad.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2queinpov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jykuqpmf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjjllyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bklefxzg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2opjqhjmb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdawvcmt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2llqihmat.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2esvrybyz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxlnmml.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfsgjij.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiqjtsv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgzquxt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcjvtfv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjskiai.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2esomkuco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2isynxvyp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2opomwhjs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuvjhpb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwjnbww.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvysnbc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2psktwxwb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vefcclym.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqlytx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjcmnco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyeoked.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pwubmrnd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mztvmeag.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgresbyz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfrzppu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhtguhf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzacqckg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqqaokh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2aafqzkln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2synaqvwr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbibbdba.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawwbumn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wdebbtvg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzdguyr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnwjcrl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrlzvdd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaplccp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqpwgn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsycnvv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozykzxz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uptawcln.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcymbkor.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2grqnpcby.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuplwrgr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjkepv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjbbero.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrrumic.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cclbpotn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fmenvutg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbetmqny.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxfdouf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2womwtitk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2saqvydkh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlljuaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiibhsoq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjvlqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgazhqiz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xirzbiln.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdjzoux.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qupwfdvc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxfywoy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2durrhnia.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlixtvli.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wfygjkpe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvmbvdk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoyrvzu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uukydexj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2axwvlchx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyvmrac.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgmgiue.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvvcaoa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbphjhvs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2giemwdup.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiohzkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2porneijt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arkoplgp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfinoath.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuxxrj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxivedd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fszlvcgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgddijyg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2awdwqtjf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jceifkeo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiynszz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsxdnac.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhdxgai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsylkptx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzjddzz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlhepif.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwqsvuu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2psxckrvf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2stkpbnmf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbvydt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cprjvzev.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tieifxbu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjolqtn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlizrxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebppudra.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbeamth.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axkjjpqf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuzprow.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ynimnjyp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfasmzwh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzmqrlu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcjembh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdrytbk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gketsefx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxrozpf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veyauinw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pprcdtnk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lafeofdo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2inqigpuc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tglzwjhb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnntybyu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhtvno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xibsnetg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfdfeqw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtoqbki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwrmlos.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nauqsnaf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kasjjplj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhwucwx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzluvba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtpnrcn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gonnmgrf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeludmdm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2orpsenfq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2aapsedqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqqtdit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rekzkizo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlsnlnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqwcbmb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgaslqj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnfwqmg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtfccqg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmrqyat.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2guaqdlvv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sojwcjyz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gycrsvrc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhvevur.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2frbusutj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzyshai.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxddeyw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbbyulx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzopukud.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2avikbywm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kiavgdph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypynyovv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjsknmw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdrkilg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwyradk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2savjnbri.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2scuvfqpv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrgdvbx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqwwsf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeuqjph.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nipilgts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojakshtd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwdnodd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiylqms.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2loduilsj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2twugjahu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpjnccm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jejljoqz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2twmzplcw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ayznvawv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmezfcv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2konmribq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2clncbyok.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiscdcsm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtqadch.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfelvmg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2agaggewo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrqbdbl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcarafv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sanhxwyj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbnzcrp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjiphvr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtoryvw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aredizie.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2srndmsdx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjeklm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrqmyim.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scsqatrc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoyyswu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2smavsxdm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiytfox.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuwfzhc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gebnyksa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhwbomo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwjlbpb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtybsjj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sirdgaqp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2klcykahs.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tamkfvfh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlmspnr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjuwdbo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itkgasta.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yacwpwdm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwkrwoh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ualpbcin.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvdcood.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rtybpxyv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bidwuuqe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrunugp.html


<!-- 参考信息 -->