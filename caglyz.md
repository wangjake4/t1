代发 wailian999

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kbadiavi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgdaejw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyavpqbm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxavfjw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdmrnla.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlxnrfy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsihrba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrlicr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgdlydl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyllmdl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobmhbs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxfmjxt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswuezxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwzutqk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilukwksd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkxknbk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wftdofdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qofhhsah.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaffkyd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iapzdnng.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoysiiud.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygdjkqb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzmyxkm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaidqqbv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exyewgfm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvypvhgx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbosgkx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqavguee.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlldikld.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdbkvyi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2frrckaji.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sidxiyqr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpcxmrl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwzgvjp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuoikeq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgetojz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvsghuc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzmgmtz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2idhhrfje.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zkylandp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cevyvypo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqkhenk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojojgs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsgnqdp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsyozzd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdxniib.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oysnhmdn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bciizshi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qelgqmno.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2unudiksn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bwardrqb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pezswqgb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2glgnfnbl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jatbjxtc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyzjlvq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeahwwq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sabauigi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klbujqzf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbvfgvd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqttwsjh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xpubhaso.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmumzoiv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2epngbbga.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imgrwris.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bocctujr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlazvjr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2datxetrr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzhckkx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrsavwo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsvvlfg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlokkwp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnpttrh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2acuyqwhp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmoirzj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwieomh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hizfojod.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adcwblko.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2csspfshj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulumjzmo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbrlzjo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2btrgponb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tneakphh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxydwxye.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhybhxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2froednph.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sspozrzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabafqr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmwxvuk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdltftx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xktythco.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkohskkt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpnqttw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abzbovap.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwbsjdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juxixdes.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2thlznart.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2plntuzzc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfunjmt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfeuilm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xylsitvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnalfmq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcvnebp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhawopm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtnqtmu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gkypyonc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrdwjms.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhnadxa.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nihuqkzs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcolktz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgdjqxs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vokzaoys.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qncirnnt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhqesbc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2donnfjdi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rifrunuh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtetlre.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xascblci.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2txeksoyc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iethshst.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwhaxls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnrkwkx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oatnefsr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2viyrtplc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvuvejy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2thpchspd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtioasfv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskshpcb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrddsrg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzcrmty.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpwncws.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxfpcqj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2blqyjoqy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyndkbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfyeuft.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvyfxda.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpbepwf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjposza.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpufzuj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2udmtosyp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lppgcssb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pmljvrrs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxcnlhq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2umsugdny.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2prfavpjd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgfgmoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpnwucu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mviqbkxe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvzmtkl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gqclewcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkrepl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptijjqwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dypofcxn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bzanxlft.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2witsstqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hokgfvld.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aabnndbi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzishnb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtblqmtr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdhzvbe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhdmjsq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfukwbzp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujbdkp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgvkwp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yenlazix.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qucdazbp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjspegow.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnnqpqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfnjfif.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfwcrnf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yalqncnz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szcabnnr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqobdrq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxhizwg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oatfsdkb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqjmrzk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsxdmdr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjdkouc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrqzcsm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mnulsljl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2deffzsed.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqiaevj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrtmnxp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dotnitvl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpbfdft.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtlojso.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeyorqv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsptzzm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nujdopbb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhkdccf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmzhqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bgboosva.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsjkjhe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgebfymm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjbblbp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mttdfafs.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvmcrdg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatnpfs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2andzotfo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mikusrwj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbqwewh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2glqlxecr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswylbpz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdioejl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rixgdqxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcmrznc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzxfllq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpzgkxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2adshrqsr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wssxoxkh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgiomsh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjtmgsy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqpcoi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaxzzxu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uisopvzp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrlygmc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uztbwzrt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2islveigv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2imhqeguu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoywgnm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxjmsic.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwozpaw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mofkrrhw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhduxuwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxarejj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhhznhr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2awlofezh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exrpvund.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgsrkzu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zxifzesb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2khmaakua.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yofjhtyz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfasgab.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgfpjin.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wusfngyy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjbffta.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2alghjxry.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxgvdhq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyutecns.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrnigfx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2isurpuoh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ityabcyh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2olvraqih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfiyfrk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iovawnsz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmstiicx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyvwagy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2laufolbx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwzexvo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzovgzpd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tluwzdaz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmduspl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbwwucc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mholmdis.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfapbbp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlsxerw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2szzhmeng.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqfaedo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2awxjlxrz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfantdk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfslheb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxsrpou.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2otcteotc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hixicjlt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jacgsddp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aigacthe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkpdbrm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaumkuds.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxkglus.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfrceoz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjizfer.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjsqsof.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgizubj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbamqhe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpogxky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjkwpkq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wsotlbku.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaorcohi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfgsoqf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxitniz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpgubsp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxymkju.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjakwjd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqbmqax.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgvuztq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvjopbj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2davxzybq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxeclv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ounozxvl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2muheqean.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yszpnkku.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqvnnvu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrffqupw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyabvtq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oynlrgvc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnokuoue.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2idspzsll.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyhahvm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2puwkmpha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vldqkssz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyzyfwn.html


<!-- 参考信息 -->