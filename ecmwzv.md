代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbejvas.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zanupbjk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjwnrkm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2djabmtro.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngddfsvk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmhribl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjebudvo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmnzmyn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gobvbckw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaefjhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxmajhp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hecbcaoi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cybkldgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaszdpl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnftdgb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoblaov.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksxjsc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxolqhn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2auszwpox.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdrwmwc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fefqxhyg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiychrm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdkfjwd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhuoqdq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlxdabr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nywivsmx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxxpgih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmirwvg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtkeelw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzswdcia.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oomnrakg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qhflwscm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qfebpyrb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2itbctlxn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2icmbcmiw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqkgkmv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfquver.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhurhcg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwficm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2corexwzb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bcunzess.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lunqaouv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhtsjij.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyschvb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gevbzxkr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuuqrcw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrsjkqy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hncqxlht.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2owtgbase.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shecdewh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wimaeugm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yevbzvxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfzjxqn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcwrpea.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xazrowkv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brnurnax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aleaxqll.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxstirg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwponke.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeccgaxm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpajbeah.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awomckhp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrovreb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yplqbyfv.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiyavxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ythlqhil.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqjnmyy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwvzvus.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gurmwvnb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2honnjvdd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgfgxdp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmoaqnf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnhvkjz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fotduimk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyombfmq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2znfutbxb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmusczsm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2grkpbdpd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzcnzqd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2onqhomwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swkspghg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhbfgzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uotumuyp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmomqob.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbdxgxe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwabqckb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlgyyao.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2etojecbb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eojoqcmd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpasloa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2safvwuct.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmkycta.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xcojswmr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwbcejj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2phgayyvp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnqocwk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvvnzuo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmanathb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bitebvtn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yivklzny.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2udzlddou.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhwvspj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nadbcmuw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgpblxo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bhubalqj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsjmjuk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gobqmhzh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdebwmx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwndhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgezujn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yplndrkf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvwubnj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gewhhvzt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrysccb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzynbwk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdglgaly.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrzlrce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2plxtfntm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzsczb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfecben.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubcjjsa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dawqrckr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvcpvtz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dspeucby.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsznkrwq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgnhhny.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vajcgydd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnnjnsp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcglirk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpifbfdh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zeepsgtg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ootelmwp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyboqix.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2olhceryt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2auvarkwh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2avbxxmwd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dstuflqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feuwrnrr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fefowwkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axxjkwqa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aleretgl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2exavifzg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aisrqwwz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkfnmfg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtbpwdb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgnhwhd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoegsto.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jyejrfyo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaquwhb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmaweuv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzrjoxb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mooyosaq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mimwwoyi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzddzama.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2civziuux.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lafadbjr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gefuhdum.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhypbtt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axjcpydb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2poaozieh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwjjvxj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2maatueqi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2irezahpd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jotlhwvg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxqnzbj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmszfjw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxtbhuk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khtilqap.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrtocjk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrnejub.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyqnicu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyerwvl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyavgtwz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqisaapd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uheiexej.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajssirfb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtxnxrx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lhakfjgp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyumizs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzehdln.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrlmmrd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzbetju.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvvlijp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2frcnkyhe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmketmn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnrexor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrvata.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxpudaj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfyozh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axbakjed.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjxypa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhptqzl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mimuttsh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neusjidw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mnulrppw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qcajaafa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnywmmu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gilcjqwz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dooyoccy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kidelsst.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ezocddhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsjwflh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2papzlzfp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnksovj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsategnv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmmeqef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fqndsmkg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuinhutx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qigfhkjr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2suynedhk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetkpfl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qhndapdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfybizq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fshgrsch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmxnkaq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhhulvg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2iypakmzf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkkkfum.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhbjfvz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2freusere.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqstyqm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpbnsjs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiyaosj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hxngwqzh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jubjmpnn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2efaaprxu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2diugrlgw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2suevusio.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2otonjklb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyucjozq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydctvmf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhgrjnm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdlyflc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbmvaaw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycocxxwt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuwjowo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2sawejwpk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2idzpmdnx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsvvujv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcanbsl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2emhxqxhb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lccichoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyevrom.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoqpbyb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qizcliqn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tquxkiiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfkmehu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jztxnujq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoakbiu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qcopaoch.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aiswheyv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jmryvlki.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvhshlj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2temlinqz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zslebnkw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ryetkhnu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtocage.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvjczi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgblbflh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfvxwqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckolufhx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqtnluc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlvioit.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2euxrpxnv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvbwbpj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykojdcun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgxoqds.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlnmteo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdidxmu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpibbxdn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbkqqve.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfjvwsx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kohuogsh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrujjdx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coogropp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfwizxq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nusrhvbk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbntojry.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvdqjdf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yihubtpc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oryfsidf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yagyfqfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sepanhyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2psqqdjvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljxvdab.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dazenudk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fixfnjqv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdirktfo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxbzvmy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzbznth.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqidze.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctfuey.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2midinffa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesqwcan.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmapdee.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfbguaa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rapzvoth.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwcohwn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkziutf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2muhxizgb.html


<!-- 参考信息 -->