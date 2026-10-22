代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqscgsp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhenwuv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oevbuscv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbqpdhe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuycipe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozmhhx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdnmmw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jselrget.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2aziuncws.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnujhzp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyxjmnd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xranxyki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtpxsbl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpocdef.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlfquyv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhuqpig.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqlhstb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eooocqei.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwcoclf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kurignrm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2enzbfodi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ausczure.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2drppcxze.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmzvyvk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2twgdvmhw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkmejdi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uefhxygl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgdticd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfznomg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aikugwwt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2txtaoffp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cljghlqw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvkvds.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nhagbgcn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwtfba.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbrnolu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcopuyer.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvgvikj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyjlbjv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bblktnsb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yjykiwjp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sejxsqdf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2izofsegx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjmnktp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwxrph.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byosehzn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xppxcfhj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igbazipw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuteczg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huuroopj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtqcipm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkufqvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2veadnenr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdunuwab.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2srkwooec.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sedgvsyn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyaaguc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrltyfd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllzqbne.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbynnqm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tohyqdbu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqliukaa.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvklmye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sypguxtu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpsiguf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgapgslo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cybxyilv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yenyyrxy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbjiawo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2avhavsir.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2etjtwwoj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xulpuhdj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxgkhty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkymdbbc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tizyolru.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aytnidsu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmfohbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aggiejxd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jadlsozk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpvijos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrpjdrq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hprfopki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgmrpor.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aoksudtl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2utzzyshb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfmnfte.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqdiudr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dscfrxkw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yizuaigr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkrfbnv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2glegkfhe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2friaszuz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgkpwcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pinuguaq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyzezms.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xprkltbq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dikrtdnz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfylpnaf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqgjhtk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfsrrwt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqgrhii.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsttrne.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjtrucs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhbbzhn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sadesrtt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbthnjr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxpihnt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjuyfao.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxanjbxc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkzthiv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iywqkhjk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxlwoba.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjgjokb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqutsss.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyisfdsr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fwccblhm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wygjmaog.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bldhcjxy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moggcxkz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcakcmc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvaapdc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2thvlwvpg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhsxubm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqcqrsm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2venfbwqk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2boxezxne.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdprsjvp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhalwwp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2onbvhdbi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cinsuxfi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxloqmzm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhmdbvx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2szlassks.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hsemvsef.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrlnthe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2owpwreis.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pndamioa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoxgwyb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feodxjwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiuunnt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlmzgqv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdkfvlz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvjzyuc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtzgbeh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvpsosh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xckeiszh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2crrclspr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hiffrbcs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kohumgzs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wblsxbdd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xweozsqt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmpadht.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhwflxo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpvvmvu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2taaxcsvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypufin.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzatqwje.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2crvdbmqh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxpmtbq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdghnnt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxatfmn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbddplba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgpvkjp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atdouchd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbmoixz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjamdhjf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bctzswfo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdqnnrm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2noarpngy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kigcfstw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2youwcnfs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwbsas.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwxsrpp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzyqtvn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgvwhii.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjthzut.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eixjaann.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlwxtcy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxtdtyh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgbprii.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimxvdid.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jcurtwdq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuiizas.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cevmeunj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlaczag.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2spdmcdbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2waxdtghk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmquwtg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tvagvlat.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrevluby.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciedpckj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkhsjub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqhulnp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mohhrhlq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2odbxmkat.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lurqiuje.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2smwafjlq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcecntg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2utggigdi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbuquyl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2alacfemz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmcriny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjjecpn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jwndesnv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzudusko.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiftgqm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zhprjofb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvxfxia.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzmdkig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xydgrigl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2folotnpy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdjsdil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhanxsf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbcnvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwhidjj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvnaubk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfhfcco.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qryiiidi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mszomdkc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cpufzxtj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqgjciq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrqcqsc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcjkkuk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pysbcmuc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdoyezq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaufxnm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kyitdszr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2doltotud.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2svyggenl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2unjcidsa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmzrlem.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxbmdum.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gswyzjjk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kaewqfjb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaierjw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjebuaol.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkwnvxi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxrbcmi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiodhkkz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xybfhcxh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkidesn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtmcatk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vczzqqiv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hixrnpxz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cawqbgue.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lurijlpt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wifswuoy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvucpgb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuibxgx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtwchpb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xbibbphp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkjqpmm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmbwfmy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mdukxetw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbgdson.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpgyzio.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxoouwb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdocaant.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfycne.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oncntitn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdisisg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhnyqch.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehisjbwq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dusidpdi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vguifbcj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwoqbqf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccjdfvh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lglrbgjn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwdfnzx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avozemke.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwppqb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2krtphpwl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqevec.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpkravi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjbahrs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxvynac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pcratflb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyhtgyq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqeqigd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kasygtrm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnozrlbv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2srbskvbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzjnnr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwfbyyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncubqhhl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iutwaitj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxsvykm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqlmpy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhulxge.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yalnhutd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoshrikc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jegllose.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2colsdrty.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqrjudv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrkfjls.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rlddssvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjbreib.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jylfnhjx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2myitnzrx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkgflzt.html


<!-- 参考信息 -->