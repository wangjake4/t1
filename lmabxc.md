代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoijtym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhxkrpw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzknlx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2trrsdslh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aodqktdt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2spdckyjr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qituqfwt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2siguntjf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msqrlhvr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sistmuqp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2scnyjkxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfjvduk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riwkiujo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2exlacidl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdscxoxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rscxhtel.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgimozm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hceijqng.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbfifkd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabtvxha.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahytvzuo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhizywrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcpletg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlidvrc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uncbwqmw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtiodbc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dharalbk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imuzhyqm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qggoqkot.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2phamvwdu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzjrnqn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxceuabu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2giarscsw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvwilhz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2trvfvqrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpegyrw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2midebsdr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lferqxot.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tzstlsqy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2avahxhex.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xfawzprz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ysibfaes.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiugtrh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnwbcrk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezjkqfm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdfkifa.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgjlsg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2biafvkhw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnipiba.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvtiopm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rzszloto.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2svrxfcgn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqjiynd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmffdyd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyadbxz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jymvjrac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2etywzcpd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdigusgy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nmumoaye.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgveigjm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2thtoujnx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wljyrcaj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2drszporz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtepynn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytayafxt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjufxwd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitwsnup.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaaeskn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxhajua.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysddaxqa.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqgkudv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2snxyrubt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flmurcul.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2maqllvov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaureao.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2alpipsfa.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kufyoaaq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2aizhoxww.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2prfkqmeg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwnypgl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdylqwmc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdmlmru.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaschtu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgzsxbt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wojdbsof.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2poatgtuc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hafuyeeo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgpgkvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqovypgb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2btgcvnsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsgkou.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cuttprlp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lulslzsn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nalnpbdj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2abhkwcyg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2clwylmzc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuqlclo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuqsqxd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rccjvlid.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lyecgzav.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iqebijoc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnpimvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wrouhsni.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gicvuxya.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mihasadc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbuftbp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmqgbb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wgezyten.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpciari.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgwrygv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkvncsg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcwbaxf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpnftod.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2otftmsax.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbshtgk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqhsuxd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwbcpfr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irmyvmah.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkjgewb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzzotbm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkwnscs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxkcexz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2padcezjr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsdtyok.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xxefkgle.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2khqkqdxg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrzokjf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcosopr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nabnknak.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bysauxay.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphxcyat.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynerengl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpupjyxq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2acqzreyk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqykchn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2livkpiuh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pietokbe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbpbext.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxjoiai.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pazmvhmi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2znegyybl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaohgzq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhavwvs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyotwcd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbyrbbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erohnzin.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvqjyrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hncojtji.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eekunwth.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tpspojlg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcffena.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlyqpnj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sivgefwc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2muvvprxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxbuns.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzjeygo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxvynko.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2buvcpqwm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zotqfcxv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjieaofz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbyklgb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mguliwmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyukzblf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ribpuzno.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stnbnfzc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzxvdrh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kexegcnu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvqztr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhlvykj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2piatkkmz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jykvuzcu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rurzewyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfcfrot.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpzjaet.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnufzcb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfwtkql.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfjplac.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2caoqomfn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvryhrii.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlqehch.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2opwlulkk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2akefqaxr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlhvatt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhliyko.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxnfadp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nlivhkza.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnxpmjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmxrnft.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmdzms.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcwjgnc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mygowssd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtkllvl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2byykkfln.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdhpnot.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pudclcgr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nctqngnn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2azxualzp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdzedyf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpsffjb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlbiyvm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubfydmp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwhhszj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrjxfhb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvlczbm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2modzrcpe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2znsguvgw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbymwfm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdwracy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuwmhoe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nydumwxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2njvlxnoh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hcknsazm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxwrej.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvaaogc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2niwntyoz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msrdptin.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyspihz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdcdnbq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yazqixxz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwtdhft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqazblsn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxqzmgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzwxyyp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivamhvhr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lrklyswy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrifdbi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnslqplw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwmsbx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pavvvkmx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqcbptd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iywxaqty.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fozadffa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bianjibl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pixlspkg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrmhca.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewpyusr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtnqbvc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2arhllddb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2daxfluwt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkjqlhi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaykfcjh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uaohpxca.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnglum.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2botcxvhe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsztescf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dujpjccn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqormjhy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoetntj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmjxncf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiymvoh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavtobsx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqpffnk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkmwwgo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2htprmjfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qhicgoeo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mwppgnes.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuljpwn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zejlwgfi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zypqiarz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvuzkqi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wepwjhut.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zosjuqsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iczenhxo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yftvdvcy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcupdcj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2esynzwam.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhewfevc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtccrcmr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrymuppr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qljmeplx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwalyez.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzijcdma.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtakrnkm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzuxhiu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlrcdzx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkpmsmh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqagmzq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpjrztl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnegrqo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtyttth.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnkmgqr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdvastr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rknurgzq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2giehtvmn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkriswf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnwhbqw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjofcyku.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ribkqbco.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2paamgmay.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2crczzcub.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dacdjswb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2grdanfeg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pojauxuu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kxafpqva.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjchympd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rslthqjf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijizrxk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qalazlzs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2esenqixm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2equfylnt.html


<!-- 参考信息 -->