代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxrstyy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmmiqjf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebpnsgi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyyrham.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdydzmqv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzmvgnr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyqtfqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrksuop.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjzkswi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2efycdujq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhqvbga.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tceabeyk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmqkiix.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bicgsdsv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvqklik.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiafudmu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgvgmbk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjujvsy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwfmwe.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkkulqm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oxamkcic.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2toltbrgp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rocutadu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2drkijazb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kobjuvwr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qteslgps.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtblqjm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2udzhemqd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkctpk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaunalc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mraxvhzm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2oursfolu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cixdvory.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuxnpjd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yjidoveh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmaiuvm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khtzrrxx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdidaif.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjlxqih.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aesaedis.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnidmllr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cccolmng.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfkjowz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqotgta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoumrqt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwzxyzs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdgejzk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqdootz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcqmwzr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbboasye.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpihxdrx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sspkvnhf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlwveo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2suvednkg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stdlobcq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpilsbo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmayzepf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmztqyi.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmvakzs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2juvlxqnw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfolqsac.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2exgildcy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2noriyxqj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ijernecb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvctdcc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2soilejwh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiiuxpk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tluredqt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjbonxh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwitbls.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bycbygwq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeniwrf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mypupevr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bglnyciy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyywafmc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2maujlrel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imnyizlh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpobaoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvdwvtk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwhmybk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvpqwfa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kojbmgrq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2juzsjyde.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2htgwkamr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwhotad.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsxfpgy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkytdhfj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtglqre.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uaitixuj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfijzxln.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgmpqiv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzlwbpu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jqufhcvl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdtgwua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzmztky.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fmebqnpa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmbapsj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wwecwzix.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjprvqlu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tionwabn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oosiluvv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pukgtohb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suyabyer.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2huoukebd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciezyatp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwifuqfd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gpknrqqi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkvhxjm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwdiju.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxvfjuv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqgdxhq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmqqopo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqqrdpr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvnjcbh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqlprga.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpetwsr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjawnmhy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtihisb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2simnfads.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmlclwf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeliyubf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqdqggr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxzkdfr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmacdyeo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvgvbnd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgtrjnh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcinkug.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhyrvcu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwhltne.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpqzuit.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmuurjy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uccdnbmm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wekjdbcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsectmff.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgekkimt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgvgiow.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiipkjn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2strgrpdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xlssywli.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvnvswe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeafqby.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2asnloflo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmbsucs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjphvzq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2twtcvooc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoiwrfn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyegzme.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyydgyd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcvdcax.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gztdbaph.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pduqgozs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2icvoploz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pskggruh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnhmlvn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwchvu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxisrups.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjjivec.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwmxmf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktddsukj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uajcvvfr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgffdxr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrtpegs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbpssgu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyjaulo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjoevky.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcplnnfe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrytsmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2diuvmdxx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmbnkyw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgfito.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyowfii.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrdngsc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hbptyfiq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2imltvgen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ausajphk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2donqjzkv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoddhqgs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hboaflxv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaujksqi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnkcueh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lneqfgnf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wheuisbq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fglekfqz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpisqlp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ioklcprs.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbogidn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gemtcuja.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qziezsqg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmrkef.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcspysij.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxmoqaz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbbqhgk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mznuyllq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrnaljf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zseuhydy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjbliki.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2masyzttf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmapppf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ckscqhsk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2arhgpjgd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2btahvfrp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfcwqfn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgfsli.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjuonv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzlqumv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2derscxvl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlruafv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2prqqdndj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unjcrcbx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqfbnpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwvioib.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bayfykrn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtvvtvw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdrtsco.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfpczav.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xciyfuae.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiimbjf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjngqsie.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgytbulg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hskboeyl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuvticr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjfugqi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mkytbacb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2refoppqj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fstnoudc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvnymnr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pockiwgz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xluggula.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkorsvk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvftdzy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgklbcjf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gglcwale.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqinrkk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwxrbda.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2icmbjvqe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxsglbr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wonnziap.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvsgsmx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2noztsyed.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeiwdzl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrbmbgc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbekosc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzgznyn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrrbcky.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgstpoc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfazpg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvfsmju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bemoqjzl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpmdzcq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2midpsdfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2atdlzipu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iddsjuzl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxztawf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeojbcl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azsihaws.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvqlvt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemgbzey.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgmbkmx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbsmxnz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfbcljf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdluqtmz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwnqou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmqgemm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrekbgz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnozfxsv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lohuhcvy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mayywrct.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfnbgls.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzftodtn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jvliidkg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykacssip.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ougymked.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ihawrkul.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2meowxjys.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuujxnnb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuquxcn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlefsvza.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvhmdrd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbjhoel.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuhgkus.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cenkhysn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkeiqal.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcczieq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tykgefmm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2broxalmm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2roqlkhra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkyvcil.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2admkyzej.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uztftqzt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2onstamkm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2txmvqhps.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdsqtec.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xulkblyt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxugeqy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvakiyde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmetccey.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2limplzdu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjaamcb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmarkan.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glcygqst.html


<!-- 参考信息 -->