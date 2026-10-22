代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onwtriww.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotmlpoo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2emczvcwv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agnhyxbd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2veggqell.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmatyjey.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cetvsofs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvciodr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2npjoxxve.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxflzhn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwbdjz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgrwql.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfgtfdu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2adhuincm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwwtfzs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2swwaotqx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrjqkzr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufixforp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjabogo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ditvgsbr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsptkduy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlirjslb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjgipiw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzmqhjz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalzgzt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwfqhfe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkycjcek.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axolrvof.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ricezmxb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uegdoaso.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpslyuvi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfipkyp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skduueik.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftktuhdo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfudoett.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjpydyg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsapmpor.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmeenss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjlckkd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrdvbcv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgeccki.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xqshtput.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aukpgffm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rloycana.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tksuewrq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2creifykh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqyjdfv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmwvtkw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zraoftry.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgntxji.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxringol.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsdwhqr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2furkvacn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgerjlz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpynipmt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyzqplw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmfpoxg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyvqcjh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2veobjhhn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zliteyjx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiepwdg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoriifk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsinnvg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuxqtaj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nxscdkop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuqnskr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wipmsqfa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjunmjc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oegwzrce.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2korqvcve.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mevgzrdg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfrzayn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigtdkie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmekxeoc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdcauct.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpndbhrx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfppyin.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnpebev.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhmzcjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2htxgpupi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoeiyqb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcfvhdn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkbccnl.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbdcufu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdsnora.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ariillmk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jpevkjlt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jchchxnh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfzsrbq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmejfhlf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wybmnuxx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjsidam.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2btdfhmxd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfvyxud.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cykvwhar.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjdghb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgpquym.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqvsgah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dphimskc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zilserzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuwbyvu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxywlqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lodnivjm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyfryrn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqbbmqa.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouznurnt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqxmxex.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoorfxg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdilvro.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibymzlfi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2capzewjy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cqysbolt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzoeqdr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vewlvbcl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddybrtei.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpgarrn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ffevrtlj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdetmku.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nwezmnlk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ygofzuhf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkmnjqd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hqelxhtj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjvxgqe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkmnjfe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjybsqu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wngaiekm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2adlphkto.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbgxiue.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhyngn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmnulud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrgrqbm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyplvcy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zgngoclu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2iklvbewo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmloknub.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnpqirk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwryoexr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjtotqq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibqbmqc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijonial.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmvpvbf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmuxdss.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tepbtrav.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzutgkd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2krsmobpt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmszmiku.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqxqqym.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zszbejjv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqdfkdf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2knzlgbxj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrdcqpj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuilikn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wcruokcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pofxqend.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahhlrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shxkfkpt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jhittnkp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rohxsccz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuewtvst.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwropah.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtadfrca.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btyfiuak.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zyexnyrt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumknku.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyngsfam.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfpabru.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiuozzn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnknyg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbibwet.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpzxexw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2culbdoie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tykrtryb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcibdtig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2crhutsyc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwchgdzc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dixptttu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmegtxht.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdoyktj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsullmf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkphdkdk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvejckb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmqhrli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iejeaaiy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sftwhvqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcnvzpf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnneupce.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2obqizbzg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bplypipp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdfyaot.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2npqcewfc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2riyszfqz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuccvpu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbbbvaw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbztmtl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnmrqmg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mozqomtv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krriiliq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2znipllqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoofcqx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2btbxpcum.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nzovvfqh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mihmoqil.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qkewnoud.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivadjbbc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2htocvwkf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjupdwxc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smhtxnuh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iunawmfx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2czkpulro.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjewxgqn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2evhuyhdj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbsljaf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgrbcbs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwuivxn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzpvxre.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunztmop.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2duaqaybk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgvlnfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrcjpby.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdnayto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgfptcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gftpjmbc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2olgrfyhm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyutypy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzfjfpz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqqfafz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoyirsc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtkpebx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaukpzsj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2exuykoml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfrleuj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdetlpwe.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lsemgkcv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mipxrfte.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zokcfpxa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcordqqn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwvxwft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjivtuzl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2audbludr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kaelycco.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwumhzx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdficlun.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsgctnq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckrmiex.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzknspi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zacmomrh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hduolemz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwnuag.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijscgfnj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wleyzeke.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2olumrgek.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmnxdrb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlggvnrs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbesxref.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xffohycr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2goaoekjh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2slxokqli.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgmusap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaqequi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwslotwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmghzdkt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfkfjly.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2alozufrj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdbmvka.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pfukerft.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2foapuslw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyswjwo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtjbdab.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aupzgodi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2icncvihz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dekribqi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2taoylyxj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkgoetr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiuhsuv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvpgggl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chhshhlu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlsqudy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfivqpc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2avfzsufr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txansuiu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiimcgs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpodmxu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejukgjgr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vawaskbk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xczpjfne.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuuuvfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksozesdo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2stfawmtu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeasvvw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2albadrne.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hswvafaj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqjapkj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2izptmcac.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2excomluw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqterxy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoabzydd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzoujc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfznlwcc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxretdf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dubnrciv.html


<!-- 参考信息 -->