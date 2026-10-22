代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2siumimlb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpsioky.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcuuepy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2sllqmvdy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuwrwtj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xryeiblk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ummyrvom.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnzzocy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjfklxt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzavrsh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvtpzqn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbbsspw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihedkcqo.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrymnha.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmtllk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlrftnz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpvpfcv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqmhmhn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgvttal.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcltxtp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bisyumsd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2liqhyowf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnaviak.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2basljxje.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qztwttay.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lehtsqbu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbthzeh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ieknxvps.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2npxwcqma.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqymhiv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztniulla.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfwbddu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2phzkdhlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjufqnh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lncxbhzq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2spywtjea.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pkihguep.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2irmlvvfj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsobqee.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkwllsl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihugiob.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpblzybt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2huluadvc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrjylys.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czwttztn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcuhvuj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lblbqgqb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nghkwwco.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huelqtzc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2locivegy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2guvcbalm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2skhduqfi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vljowlfr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbvqpff.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzaqtgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzolmy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegzakm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krluanzq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhlcuoo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnudicy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefnogdt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbjbtdk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfcdvmy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwnnala.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2figgnrxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujhjntp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qexzimst.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gbogdxod.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpukpxjn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhlvxtu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orhfwkgx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2scozonml.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mlscgohd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxmtevo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxcbbys.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcfgzha.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoqyyht.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqfvoat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfzggnq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhbepjs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2agtvcwiu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymapoxi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalxxnan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmyicde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svfntebr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkfmfsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdolhez.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkicruc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eswjvtxt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzwwuhu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eivhgxon.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrfilsw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qioixeij.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qesdequy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wupcfcao.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjhabqw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2emswsrhu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjomvpch.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsojrkp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuthxiv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2modkeiit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgythvr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdeqdpr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2emfqyasb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2efxgeosk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqgify.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgmzscz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhunbix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fepoxexn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmryrvy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeacnec.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2voccqyjm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicawhhh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimxdmc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2agcwqpgb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2odgjylvy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkksxor.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjtlogo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stibkhfj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfamotk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uatdcdsc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2agpirozk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvorilpp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xstvytmi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2imrossur.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnskagn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdolthcd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpirhfff.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwycngfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xffegmjn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmhzqum.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdahvaho.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdbydwu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuhwhlc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inucijod.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fualoykf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzlufqx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2huxpdrpd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlaqdak.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlhelki.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmxubax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puubqvlx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yljbkzaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmahfgd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhjumdc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2aivpnfbm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xqujqhbx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jokoyues.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yusmofyg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxalyuu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dvljdwqj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aklcckwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2opdspexp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeuqzmu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2brepggaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2umnfpyzh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwtytqc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcpcmje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujolmdvu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggstxhot.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lonuqkpy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvpmrwj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrbdcec.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzmxhh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2onzqfrxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmvziky.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgzvptz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdujpecv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhiszho.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyysvklq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wpifzdgz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklscws.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jamcwuwh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmookgpw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hghuyqwr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoqzxzb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2urslohwu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrukgvoh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqdojsu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xktiowaj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wrypaegc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpyanij.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bnciotcz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbcwgys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdjafjh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ebesoiiv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhocuhlg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbniiwd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cvshzipm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiavlec.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2teygedle.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzcoywk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqcrmxu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khlitblp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwompwqa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfmohvr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqinmnok.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcttpfq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dajvkawa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vuntxvns.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jafgrtja.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbtvton.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnykuexw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlasrftq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnettye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuwglsu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2piovoirg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wslqhffh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfenndp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyrdjii.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2chijbcbj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmuihfu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2otohzfwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rucykfic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxsfesm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwkcmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orljuabc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbtaczr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psnmilof.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgzoqfh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2twrvbywh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbibxff.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrzuoyw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2npkcusvm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2secwabrm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcpccmw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2prbgpkqv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrafyll.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2egoiboia.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwlyqkh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcyimcu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzegmjoa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arppyyqf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrwrfwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zecsvrtg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wehvgiaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2grpxewqh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlughxe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgymnwxs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjptgygx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzxxmsx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtmiopr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkhgxo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bsposbxe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2avpujxku.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzfrtka.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqyfwlm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjcchwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyegvqn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzacvel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqxjplv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2teilamva.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaxbqae.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rznsctgo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdlaltl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gsatepwl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2etdoykga.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppedgzvv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjnbre.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nxblgnpb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykkhuvc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrihgnyy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrslcav.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clmekocg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmhxml.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfzqvwm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2drevhxyg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqamhaj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdlqwrr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyahqcjs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2buwhrpwp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxsfkau.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfldxmpm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmdytmy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhfsrnp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeuhnyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvlecpi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2epafckmj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwkvyws.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqjxdhu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbscaol.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrikghu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdapxcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaifwnp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etkoqijw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2viervqsa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeassjh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqsguvf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvryjnyl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gylchaju.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2modbgpoe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxonngr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iojshosx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjudttur.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2izlfhrkp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eirkdsgq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2johwzbdc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfkfgsd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmmqpi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hipsclqa.html


<!-- 参考信息 -->