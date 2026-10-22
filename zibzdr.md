代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlfzwet.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeegqnc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tabruulp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uajfclip.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prffnenw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aemkkeih.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpstigdu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoangnl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2srjpniof.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzvpfuk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxmywqj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfskrnfm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgpriro.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiqwvuq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqshbxcf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2radlqcrm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2baiszmsh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2futzcdhq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqggtxrq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mytmsrkm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiyyecy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2meisjppf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2teixuygq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzlixha.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2icuyfuna.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgitggw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpczguno.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2inttupof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyyfqvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nikcahfz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qksbgfwa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxrljfz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uapqpbix.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2drfzlnoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nzelxgzq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfrczqg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2buizzone.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyucewq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tttajmki.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhynlxk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2webqjuqs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvmnnkk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwrtcsc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvwijjd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2toqizzdi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ripjrvti.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfrekcg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmzgreg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsvnmcy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqnxllm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gtshzewc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxtccv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvdfytx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bawotrjp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojidmevt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heaamagr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvohqcwp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwuxpbu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvltqwp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmoclzm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydgkgwb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clcwpfhv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zeldjaga.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fslnmoil.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hndrogcq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwipikmu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqfnbif.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2booteaoz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpltqfb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhtjorp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jchmiyeo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2azsbkzby.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgocvjg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaoxsnp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvjezjl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2snxltvgj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgqofvy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnchqpzi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2saivzjik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvzbzff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsenndbq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wodzrdek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjufyzz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2abtvqaud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2brszavar.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jomcwgqv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ngakocym.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnsqtpo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdkwuet.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvwsjqz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuryvkan.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2igcqmteh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvvzbaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ippbafua.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjsrndi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyxadts.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2klrntjaz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2keylsuak.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2utrzeptc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzbqtsd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ghluyyut.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2acdfujmh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiqkmyf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xocfogxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pxohljax.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgmzftx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arhthbnq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkkdrkg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zndgkofv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klpcaovp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdyqejw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zysdkyrt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bynbtqoi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkfmvjm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsjmwrb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2trvplvfp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiemppr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlxuxjp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swhdneis.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2njuqbgft.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcrvsne.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvyjvze.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2trevbbey.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbrpsqd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vennduvo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pywmouyb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxifxnom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaumanrf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wjysbivi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yobkzrri.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awduemci.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smivtvci.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uluyvmrs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lormnajx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yfknlqac.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjrwbyc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eiojoeco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czdngsro.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybizrrmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geccfbze.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvfookb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdmupia.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcggetu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtcccbl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kafphwho.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zivynvjj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwiajer.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhzetvs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrskfbj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqtpwfj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pumrnlun.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnmjblk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqizret.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjmevwj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicmgukv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgtzgpg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2svlsduid.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2phrjrvup.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xiudmvei.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ongnhhtr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgubbhr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubauyjns.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhasrtn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2whhawkoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvrmntq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jinrzsau.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2emfxsbav.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fypugebi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qydqehjy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iksycoij.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqhmxse.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dewutlhh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhibovo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfmbjpk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhfgevq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnultuq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dgihwaxo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlrdcxy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oxucrcdu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqhbdpl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwphvfpx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mphdzpjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbktccvy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2otjcfdft.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2iszvxkwh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2azjyhdyg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyrxeka.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtselmgv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vpddrakg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcnsimb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqwjjwv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcaqxnj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussxkmxq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbaozub.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyntnaa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pravirhr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlouwhc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycziwhua.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xesrtvte.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlhdipz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iweuthzl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsehisf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgykszg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbqkjcz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoptvxo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2thbjxhvz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2guuhuwrs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzbttcd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwmzavf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2boitmgui.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdrrvek.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvgkbly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtglble.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vadcjkgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cduxhals.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mamavhdr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2brlvluac.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgyducv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xknezqry.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjmncao.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwfsqbl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiklgcb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qifvagdk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2epphnaco.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jblwmioh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhncmuij.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xictqnef.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivkwckz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqdmgoy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmottew.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyquicaf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrviwkr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oizyqmky.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlokbbz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwputyn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpawnihr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2offtcmsd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpaugsa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oodtrcee.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnwfurt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cutsclfo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mfklzlrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvhacqh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcztawf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdlgqqb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vekvygzl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mkimwdym.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqeuluq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zldcwxqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdtjjal.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jkixxvtu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rshcnpvf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qozysbae.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhyoope.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2thhljclj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nxunchtm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgusylk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylooelij.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csgwhval.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fypotjij.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnksnjxx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxdyhew.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2otlayxeh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hopjokyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioimefen.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezipovkg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqltgnoe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqvsco.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqsxzia.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugewhtys.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rejngxbe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2irzxpxdk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgmhcwq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2istzkxku.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngfnhzc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fpegahvo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqirvdb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvvheue.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiocfmqw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzhbon.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgzpbzx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrhdmtu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqcfhcc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2amkzzasq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feahjcqn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiknden.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fceupzqr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cowvixhm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvxkndm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeyebgf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hufostqv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mktmzbkd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnujhv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgqkqea.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxcvug.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eekiqzpr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2khthzoxf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohadivmr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpltddr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2itpkozpc.html


<!-- 参考信息 -->