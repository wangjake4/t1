代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrcivhn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hawlddzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmklkek.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eayknjyo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiqqepm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvmfdui.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbydclt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luypdwmn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ashojcjl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvldsdye.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpddxde.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxsewlv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmzgmsc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxwoqup.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkulmvxd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdeuwcn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvirgcp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2itzlawdp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovmasw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcmczhk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2maquryds.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2frozryxl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlkqfqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qcykjkif.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkjufkd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqqnpvv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qppmwemd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2spveubka.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vxydipnb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2majpmkwg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uxclaxrs.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rchrgnol.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmnpalq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsxjagn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tualvzpe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjjmrsm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cefgiahy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaciych.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kuorrntz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2acgmtxri.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dczvygry.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tidscwgh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyrnwlp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2udwwqqlu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuoriin.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpscfsh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyhmbgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znlygsxb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkhdpuf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2diochcvj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhorvkxt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxnvrzw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnolkdlx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2acwnltup.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ersstcmp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaywwld.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkpmkgi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdlpgse.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lybgyojx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nmngfsfa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pooqbgsv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2htvndmou.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ledwbmwf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlklamf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2founvqvk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ploztoml.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vctjllwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaflzxz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2muyqzlcf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qavshuuu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pujcqwet.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2okguzuoz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwiyxrs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgvgqiu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dovjaumx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bknitwmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbhteri.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cicrsbtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sludtzsb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2reassswz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hosjcfqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyumwik.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rctukonr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcsfgap.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mztrrleb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyniayv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2suaxwfmn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhhlnyy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gltmyywy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwyjmzq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tnddhiat.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaryquu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyglqfs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pspuxnpd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyvwuyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnkdvqn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hicpsklq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdpyvt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bohdemis.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2chudyryy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qboicuke.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqqiakb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwdafrt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2usafjifn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2koealjyd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2illtjmng.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbpkdqc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vudaupcx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sjamwlsk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmehbiv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfyuuxl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeyxwgo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2halvshdi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxwatzu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwikurl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zyljrtxa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwcrgar.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aaighfvo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2youiitcf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cryuxnnr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2czlarwnv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2peyykupj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvvtpxb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimanbbb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaoqqip.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjytmff.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrmoatp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmfqbcz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2klcrpeik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2txqyizyi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2szoquvlh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sbggbcwz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mprtoxvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weanyrji.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhrvqru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srpjvdae.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wssdvjpv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdbrrng.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwrzrg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmejwdj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlreehhe.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmloocci.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhatzog.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2seluyrvm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmpgnrj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaiwfkn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtlggeq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oksecocv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyajymt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtydube.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2myohbqyf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvjcywg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsetvl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhvqgjt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiwrcqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgqavme.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeikymyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnuvafu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoajprw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2figzctfc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsqezkj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkvhywa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2atlspveg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyerqrg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbayzejz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2huzsrikg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqusbfb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2chkfqxxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sytjllkg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyqebtv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gclmhnlg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2srkqwpgb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jeztmojm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpxsysd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dfynbzvd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqzbvpj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcefkvy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgycjsu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpldzrh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqofsaw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqfkxdg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlendmjj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrovecu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrvfuon.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yffyleqg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sorqspqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szinqqri.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwrgyzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2idfdhuho.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjuvcke.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aspplmrv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpjejbn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfmszum.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkijnty.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzpdxjq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiewsai.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfsrbuc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yszwqpfq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uvutvhhg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2czemoeay.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tefiabyd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfpqpo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mshxwujr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdcfllr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2liizviag.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uuroansa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyruvnsb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nodcafxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvysivqg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaciprq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdiaqtm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrgqvnv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiddugc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjnnnao.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2azwtyybk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jforvkji.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2orezdxug.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hparkjgf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgjbbsf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2npqqozcc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpduvxp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhbeuvg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wuilouxz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2juesvouk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaagpbgq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uujamfun.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbrxhbg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdtbltc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbejeiem.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yoinldft.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgfwpee.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgezsjwc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzddhcvc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xducsuqb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdkafcy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mygbgnis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrwdech.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2btecacpu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsswahd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2htaeypkj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gffpktqy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lodggwmp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vgysfwav.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrxwwwf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hamwwmqu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vficpoqx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjylyoo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnjehfb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydakmflt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaeebsz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnjjggc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhvchgg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybmcav.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2beevmaop.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhbakb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfozyrox.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtncnea.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2klrionun.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eleegmtd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqobbpm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzcursz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwvhtfd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwieayul.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kounafww.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzylgiez.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdgjlac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2htccavtb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlftknr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oucugbht.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lrphahhv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pamhghhk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2taonhsma.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgykdxt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxewtxo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnxopz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovetbtho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqwdbbs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vryymzha.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wawmpefw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wexnevub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tshezbst.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pskbmmxs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkonzqm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jynxtkic.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzduieo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adaotexm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpqhzzq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2inxbbwnn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwedwrt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sinkrehl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xibscqer.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgyomlw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmpaple.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcykzmrx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gluduozy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxisyvp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kovohlyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqjvyow.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzeanjj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2swljxaok.html


<!-- 参考信息 -->