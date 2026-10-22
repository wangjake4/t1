代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osczdhub.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgldcrdf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2opfonqgo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdfbmwj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfayiul.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqaljoq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvgessb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdxbloe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbvqqvt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2weajrmda.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaytfkj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hhelgyko.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2omjgyasj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2izpdoynu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnqckln.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2piumjshl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxeagus.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxauoxws.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbuagq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgnidlf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtyndcu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlgzrco.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuywnfq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzslbumf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2icduvpgn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzephskq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunckyba.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knqwtxqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkyjruq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdmfrmc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2smoiigkt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmilbwb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eczkkjyb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlvztes.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxkplq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbzitxs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2orpucabt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkevifkl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdmqua.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgzqwqz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ddidhhoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2chckhsxt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfzjqbq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfjlhnt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdmqpes.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhjcfud.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfvglhk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bauvedat.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2maphtrjo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgsddpb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaclhnp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwhnxei.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kltbbato.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpeweqe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjktzts.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoutkyp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjgnyps.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzaxyjc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ecljiply.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lenpujwy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yszfkkby.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2csktsnjf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkazgoir.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmyuzqf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaogmef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrdhyyg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeasejx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyagecz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgrdxiy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrbzxmn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdwooxi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdynms.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvlgkou.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeppgkr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjifing.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrtkorc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtgzknp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdkyngt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfldan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ondehmus.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acrdcjcm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvjxpxx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtrynkb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uymrjpza.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2coepdbsk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vugjsxgo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgdlfpu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2byknpdno.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcnbeqi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfdmrnt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ylepbpcy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jamortii.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qftyhjim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcqitcg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oryvcphc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vberhfhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyanqmcv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdihutd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atsjdbka.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uguliwon.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxijtml.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyxbosd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeutwsx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdheolz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wluecpef.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooggpixa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvgbpbm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhnjuuo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2flvunzxe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdophaik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cqieokmm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yksgivss.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2knghbvcm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilvcyqb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnouzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpzngbi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvcoijg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2brilqcjp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2agbldmmh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcqcvix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eigltppa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjbllce.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfvbep.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfyggbq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxiaudf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvtaqhk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2djxekkhc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfrteun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiobugb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mptuwxny.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqroips.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvpiwgj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eufejjwj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgugpub.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkosqmnw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqtbdwn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaofnfsg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiidvww.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuipmng.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfylkpcv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcsfson.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2beyfqojy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfjawyh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rassglwl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2btmpfwen.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvsibfs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpdfmeg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgoecmr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2elrasamq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hikjndnz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtkpemy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsznfrk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfqixxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpouyst.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqgiwuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzwtctb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kolgdekl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqsklxn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhtvamj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbhvsr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyasvtwo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2obrnmlxq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnrrtr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vntoeuia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uobbaamr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzfhknk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmbpjoi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlitiih.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2asftudbd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2faywjopv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgjuzkz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbalnlp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2igtgvgle.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwywyyv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rungvgpn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcieuzde.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpylces.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwihzpu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iipsiodr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlonpywu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xndvlkwm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckpuket.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hahtkfms.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiecfvv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dcehexrm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2welpqfvj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpswewu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpparxp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqdgyk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvrhwuf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kunkhvmj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvigyw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiscctu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xmheifux.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yanjmdbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiiisto.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjhweso.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2loxdboat.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgmdrhy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zjazeztt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlfkmzw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nltzkhhb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpdpzkp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shamdpjk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjocduw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soyixgxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmxpuez.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsgorov.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfgcnp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyefvjlj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qggpkrmr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuvdpbm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqpeidb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qejnwhpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gerfosow.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnehdzlm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmimyq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyonmrg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqoqcid.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrbgeyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjmfeew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gksvjpgn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxnblng.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2precsmbp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zygqwwkw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgynwok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkzdlbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sosugagw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrhnrqf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2shicwlcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmswchyz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2blyaeptk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbnawa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxipfnya.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzxsqhm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbdavj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehgclo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuksslof.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdlzym.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2whjqfuov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hplltiiq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjykmuup.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlkjicq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgodsvw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqliifd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrzvns.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkfrieq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irvicwwf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyowjeiy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnbkevq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tffoqjtd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtkfii.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsqbkmk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjnmrds.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzwbdsb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqgousx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2erddetaz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwoqabc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbesnng.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgyyktg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lslrafgt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbdrpxr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxminen.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dluruoib.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zctqkkzo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wolbngpu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rapdsztq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzcmsbj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtbytcy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2akgeprfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuwgnjw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2urbyvlqy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjohxjao.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2crcrxwni.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjptqgqd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qxomahsv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnjiqry.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xomzjnfc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiywcoo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqyoahe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiccrtvo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tudalvfz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psifqkgp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpnuvpp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqghlbl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdsmoln.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpincvna.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjusxya.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cerfetis.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlspycx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2julzqqis.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbpjozb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2owttfpaw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mptrpytd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfboztod.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kizdzhnz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgqwrct.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wltrhqxc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoxtkku.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cegllpvm.html


<!-- 参考信息 -->