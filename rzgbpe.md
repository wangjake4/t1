代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2asxrehqd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuureajb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnygnts.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwfrtpi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqeksyh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwwumto.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffeumba.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnzvbcf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxirpxm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjhwngr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbwmxpb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiigecez.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xicxizek.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjflytql.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcdchoq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbonnaj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oovdpnqo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wouyixpo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsdflqz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2curxtjch.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbsuehr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2grahdexm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bespfiwm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ghemayag.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuxgiui.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2piqesqfq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gumuxtty.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tprhpbpw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtvqrto.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqhycwf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsyyksp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2riojzmci.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2alxofscd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zjedbucw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2laiuhjrk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrahbvq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqrkux.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtenhegy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkkpfql.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pldqcpil.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plxjeyxb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoohpvi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ybebxmcb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plddszgh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjargmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqirnlf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drdjkpqp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpkfndf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gjutzylg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbkiyrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2spkgnavd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jllwafjj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgnbwv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2osquzfvh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzomnwkv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcxjmng.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdutqgg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2meivbwjl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kocjyeen.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbslgmd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqhywwo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iceqcaqe.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uocjeavk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tydsahyz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmwjdzw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2foayflsy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyfxheg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtdoofj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iazycruw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tmogtulu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2grospxwb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxjeow.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhoinnv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkdirlx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoubglz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxufgyoo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fwndhrue.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmialila.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiavsijc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ainmlxxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afjripou.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqpwhth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dycaapzw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aspfmaju.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdnticq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqfsvxa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wifvhvna.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtiwbih.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsspgkb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bibfdqov.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbxsokb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tebrgfah.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2keueqxbe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwsuwhe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpqrmfw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uutknwhr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnerbej.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2amqupohd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkslukp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2msmfnues.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xddyecil.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrkadyb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xknmulno.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2boenorfv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2akyiafmd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2icrcgjvc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjggjbiy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lybhceci.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yypehddn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jccvojjy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hzltcmra.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqksluh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvtapyg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fymwcxuh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sovfekax.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdosdab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aoecoabk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrijhyu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puckxjuw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kkedwrke.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lucpznso.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2utxffssz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqkbllc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbirtxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2asgggvlh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2warunvpj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwjthzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbuscqn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2akhqspef.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxhjtk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvupbrgn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcnkwva.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcuncyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xcurdomq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdzaqgs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aohubchu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjrkdfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyijhuvc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2behsgbkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxpvxfc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkvitmh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwptlcb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrxluhr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tletoink.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqntwhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsdevlz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbqbwip.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2igsjqmqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrsjubx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xirfuvaq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xclicdxv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2btiapwwr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2khmxypku.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfilnyjj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfsdamd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhmjlpg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpyosjp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oejxluwz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ierbzcht.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrqfjei.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrlrrol.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaqvngy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igmifuxr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2chrlxcfs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fppasrbx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzambb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qutzqppp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2srgjnwyn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwwtywm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnxuqbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfrohfs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2guzpxlfx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2drafsojf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuesgqcb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uduedryy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwidlzi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2twrybgox.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzmycog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcwpgvw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2szqwfkuo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmubkoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsbbity.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2timzmmti.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxjjotz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrnqtnu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiggnng.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hldziwux.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niozbrbm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bgywjick.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjavzdz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whudwkid.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaermgdt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwlroml.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kshhtdvg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnpsruh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwuxbnm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrihmhob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlswedi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssonfduv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ympgyrlh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfxvnm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzdbhum.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2egduuaxt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqgquck.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtafjov.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqyzljv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mlueicby.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kipeqioz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqpluzn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wimiykjs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2anebueig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2iykrccbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urasrwfe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2imffrgvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btsxhgnw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrlpkis.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2luetnphm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwqebkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2luhtmqmr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvfysqi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mcswswgv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiecoocb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfanovd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gbthbbqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2esvioksy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxauihq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xiastlmu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdljvz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwkqenh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhefbdqc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxqelb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pehirfds.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtiovt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbveptsq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2omnckysy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwfgvpx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmetsws.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtamnpn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clnhhlon.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgsrimk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rebtbmdm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqotjzrd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznqsva.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yaosccok.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wogpeqft.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmahcdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sapzpqdh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoduglw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaiaada.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtgicfz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoijqob.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2armmcqrn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpolpozh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeccrff.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhubwyo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxsiikc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywuppse.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlijrhcp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2injpkvfb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qroiqsvl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcgizdj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2otmeflua.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fclyjfjf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbpxzni.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kijnjomn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgrfkpb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2chqpxhgj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bpriwolt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqlcsrs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgnrke.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2clgeealr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvxetah.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjzjfqj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpmtmgf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmfumkz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ivocqdzz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2laudqvqr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhojfmy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alaarrxs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqirnij.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slkokgta.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rnleygfw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jckuexjp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaczpfd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqrvlrh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiimwyh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwtwldq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lwftdtaz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyuynyz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkhhjjq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgaipam.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjujlrq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2btepymft.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kghlpipp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvwxrcy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vqirmzvc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yztuglbz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwhqhfg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hdupoadj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvkmixu.html


<!-- 参考信息 -->