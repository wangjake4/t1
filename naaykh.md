代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjwurzn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqedwgtl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmxdckp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiosegww.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2falyqopy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfnexgo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcjnmzd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqejlgcl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulpugrj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovscoxik.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deqqximw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rekktmco.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxveiviq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvujmok.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqekojes.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gutkrjnk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvsdvdh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdjasba.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrolwxsw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimivuyf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbclctf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzujyzm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2izaftuog.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysknmoj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvzznt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eylszgko.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vwahzvto.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxvkack.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsjtfd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzzkgel.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2oekhqbqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgnibgb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuevzrx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdnbyag.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzzlkdl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeizdmf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2odbduqgg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvwsuvi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cttknjzn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujysqmpz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdciklg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qezazssn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbqcfcu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjlftij.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcqadxn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gmelegrm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gddlxyjl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikowrxbn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwklmw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlyqvxl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yridugef.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oibagqjo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuismoc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdkpkvp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ulptgubd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrlgzgc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvowokg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvxwpqf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhxevjx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igflajvt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfibxkea.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpxcnpw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzehjjj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2buhlhsom.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpdymtl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkcnspx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmyptlb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqimecv.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyyehzy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mfntydcd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoebspn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2elgacoig.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rslhjynz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2klmcxvnh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2envzwvvv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpqxfov.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2husggbgx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2riwyjeuv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbadmcd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2knpirmmo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xruhcxmr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pktatxdf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jprsakyp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxkhne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqjhtx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfivwga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdudxspm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2odrfuhav.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2larvooxu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2weepopec.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eplerhqm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2selevlue.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvvznba.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwlntg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lndmlazd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyteprr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxhmwwz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdzxkug.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2abmaiapo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvjyqbb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpkfzrp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkvzxin.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzywxujk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tuteooxa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gmommbtq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wroakfdi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rynjokit.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gfapbvbx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ffffnjqu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2giwzxsmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkqsmxw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmgbtez.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebohhcmq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duibqstu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdgqypy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oczekqpd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzujxit.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrrtgfv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkwcemv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ueztqjhq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirhupe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvhbcd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvheknun.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwvyxjw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jthqqthc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyukqul.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmzltwr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuflwuam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2stepupki.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mracnpfv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2whfaktst.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhcsnsb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgoyqkm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pviupftr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oatwspva.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkiemmx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2udbyxkjl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pdouigcn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtwzujo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkqzgsw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzepxko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlhoxls.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyikckt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnhihmf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2msbjwzaq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxbqqxh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fxneddho.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzonqqbe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2krxhlpai.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2leargzxl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpiyyfg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aclzwwkc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxtqenm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lafkjtos.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhnxdjh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozigzunb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jqecrxbe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pztblxxi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcasnuq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2agezyzza.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oakftmld.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zokfcaxl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrndlwo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkannuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyigivqv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtaoxpr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwgnleh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpafncq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iclvlbil.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2prbydzjb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvthuv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oavnzuny.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaddbsu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nybqlnyf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oylhnldo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kdarkyrb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwbysu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqxeakx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmdvsqc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vzodwyli.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmphvsb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnpeag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxrzlcg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cbatckjo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbizzoms.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmuqtqt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eizpkxun.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fyewpizn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiqcnmw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvepln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwwizcb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkjhrqr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xidnozce.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhnzyso.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szmvkxpf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gipnjzrp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsoopbr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhmkqxp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvbuzgt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xtswthvu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqnyjlg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qonsjypu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fijmqboh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdogrgl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrabzkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlxnmig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rezarxea.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2naitzycx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlurlbbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjttsmsa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cctlsluj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2waezhmkl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2axhqnfvx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamnteo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfulejql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2exagkmrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpudjier.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmvpbte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiwrpeh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2poumnlnv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fftapjhw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2okpdimww.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmvdujg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzrcih.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhzinah.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixwtexa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvpiczr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2teypywux.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaeggnd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmcvlgn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ywybtpjf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzejpa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqsfjn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljavoxbn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dooenfho.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiknayg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowxpif.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrlaml.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdbajtk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkztnve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzidipoq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbcuego.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgnkqw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2amwisbuh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsphhzm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lfykjucm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qruqdapz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eifgopzp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jreeqvtv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkatxtxt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uuelemcm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsmsfao.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2coqhlyjt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2irxzxmbc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdhmpas.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqpwntt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhqmqhv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcbdowz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuavblmv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmylof.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncydsdoo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvehsdph.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtgpczy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuvyiao.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lboutrum.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aueuxqie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmptcokd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvoqedn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpaxgnp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2buwapdce.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjneaynz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnyqptb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojgnif.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzyisrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdftoqgc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkiigvl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjefflay.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiohanb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gapmmjyo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vfedsrir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwoxrwq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkdzesv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jckhkkru.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jufwonxz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnonpql.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bbardorz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvfopqr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqezyxfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sntsbphj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yutpawsd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bayeujqp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itkzwqop.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkfcjak.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2syaiqfti.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2woamwbrg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fdggyusq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlgpurq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsmrshv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbpybfv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jpytdfmg.html


<!-- 参考信息 -->