代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrwayrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sevisjib.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwamhgr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbblsegd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puycpsbh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdomhmhu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavpfoss.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2agtwagye.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzwkjks.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeeektw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sowfrsyl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxwubai.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adysxzin.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2klkjbymp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkrmxzs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfhjgsa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxmxrrb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wphbupvr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eliwkawt.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxiysfc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiozuzoy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmaiyxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2czigtkuf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtagcaos.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhktwa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaatboh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrwcegh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfghygu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbszzbb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrqmhcr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkyfjwe.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2papaduut.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cssoagpl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vchvpfma.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyrpqmo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqxulr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoqumen.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2otzwqjxs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfzlvup.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tctmqrts.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjmvjfp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqvzlug.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zllmgnag.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrgpzuj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrjarsw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrqerex.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahedrrei.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2djbftjjb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcwjnnf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwgglmr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kojiiflx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ietitsyt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjmjzqh.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hximuyzq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezschzfa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnqzwzb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqlkxzv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2seszvpnz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjpckve.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdakdzws.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdphqpyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thuugqeg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqassyz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2juvrolhp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2joahxlhc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpmshyr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaaudsd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hoshsdvl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrtipxy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sznizuot.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bawvlytq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zczzmecy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpohveg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2umkjnznr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxeddmf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaoklbz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraiyle.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjwidps.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iobeefsx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgstworm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frzjqctx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xofowstc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2insopamt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mseuadps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlpcjaq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjrcii.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2evwxeygf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmyfvie.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2abvbdkhi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2okujygdr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyqlao.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiusafa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vbueaeao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedjvqv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrgenhv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsudbix.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmuojnp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2peiidlcv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsacjzlp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bucxjtcf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwvcbaz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfreodz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpbprex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jeihbtqg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgumwto.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvqsckb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcegbryr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbejejih.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qboifagw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwfsvxs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwccvhe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkictwck.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yariwwcg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzzcafa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbakroxo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdzmthz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tylkcrxy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2krneuzja.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzudutf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2brkadfqp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rytghrvl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nerkpnsf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyxbrih.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjxwxdx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qczqddct.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uehlagml.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwcjexa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umseqcin.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdxvcpg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2igguumii.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yaylnung.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiqrheq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhjyrue.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lqawuqlq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvsjqpu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdmmjr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2caukrxzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzcimu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzcdcbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmtgftc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtxfqfl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyvohja.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jboeiivc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlscnvz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdfhvwf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kshaaand.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfdbhjt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lcefpomz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btbovdrs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpaqqn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpbfwma.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2udyjgnij.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfwiyap.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgltekhq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwwasms.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2atdaehfo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyishfzc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkrfful.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbiaszo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnbcmfl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhzfaob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2julipmvl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2coopmxah.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtztjvek.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfjakkk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfblkp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmqkdea.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnhmbcy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2joundkzh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeyeuuh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gizvgvbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwzltfu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2absvfpit.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvtedoo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yzobnahe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmljdnp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bgalabyb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrlozrr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xszpohsf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvrist.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2piiaetih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuittmo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxcfud.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2afomjczv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2uatqpaji.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwekxi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkgczl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brdccqjq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxxywzk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkqwwcl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wylqwtmr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvryatpo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzjaqfq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrurala.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcrvwhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmqykyu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yebntsvk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mokzhsex.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmguiko.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrconmf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zxndemij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jagmbtlk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjgktjq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkoznfg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrfrbds.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtqfsdj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2whzpkjex.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyadmam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aelxidvl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yqikchgc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyohhsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ueecmrzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gotegita.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oztjvuin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzffwwqz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjfbizz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tophnfax.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwlvnoo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpudilw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vullstcb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmaspjh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmpxppc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rerhnqer.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqpbwlk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzpmfmm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2imatoims.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzwbrih.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnvvps.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2emoukawy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eylvvdge.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2efbpsvii.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kshhavaf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfzojix.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswxdfi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2okrslpiy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnvfguc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeiddve.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpiqudz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvzcnzb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yitlgwyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbulibb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gnccljou.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2swrxipmr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pszmuftr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lbntjigw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkxsrac.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2laefwvpr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfdvbms.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyukxle.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ovikegta.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjpale.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkdrlaj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzwqwya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfcgfdy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuvtsbx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmhzgfq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlmvrve.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oilmfbtn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhsoxy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrugekf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2seojcjdh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2icohgnog.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjppkyhw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeobrbz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jphmbrup.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjwdhjt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjzgluq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzeguei.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvckgil.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzenmuq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzyvltm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oropzhnc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzzowxw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzhzzqd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axweqevd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkruzvw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjusvxx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmovziro.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfwofcr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tojaidne.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzmlmy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tahcpbzv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzzllf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwnqzvv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hegxjown.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2suilnofs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctjglzp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtaufxf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2detclhci.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flphxwtb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjjgzku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxluwuq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fsutldxk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaxxkvx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lckpafbr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkijxs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2taieshzg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itsciveo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwgvmgo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzlsmrj.html


<!-- 参考信息 -->