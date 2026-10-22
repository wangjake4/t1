代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2udvojxod.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ccemmtgh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxlbyvq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkltrnmb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnirsyl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttbsbtp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhcepbf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbguvxm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcugeigu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaojpzjf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvftcxi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlkzntb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dssbqims.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gafdexqk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctenbpen.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poidaktp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isksymgb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxecnng.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwyrfyq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsbjkls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzudmqd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2igkjpwgt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2efggvwen.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzvmdey.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbrkttq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpogvhmr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsrebng.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guvgzblz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jzffebih.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyayzkd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkagqkn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyrbvkf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vdenbzvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzhbmp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jstcdjcn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vzinspsa.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2geremnza.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2huijvwai.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcwlvha.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgsikqy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzmtmld.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrivapvo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dctgxdha.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cutkelwj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esqkneka.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wywcrpcw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2emlfhevu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owatibdp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xilzllgy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyijurft.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgurrqwk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhmcrul.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbitkou.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2clvydowe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsmcszo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anigtxqm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfkxzyd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqiyuu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oveetdkd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkjwamd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2heucpatc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrceyli.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpscxgqq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctqdxwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eedygmkp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjwqgee.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkcwrqu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxghka.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfsifzm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2clbzrcye.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yebminbw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabkxqv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxfnuux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzuczmh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wayurunt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsemhhk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfjgwdk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rttbjrbm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvnacaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqscpik.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtqvqyq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jijbvwep.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqnzzwh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcibcke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phrukkon.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2feweeydz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtcfoqh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mntgrtgi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pirdbppd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaepbjs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2afeentqt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dusdkuvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nikaslmp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwantbt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzpxif.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmeiuqk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dfakdgnd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqlfolx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2keycisfd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfjkbgs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzanpjk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwczwk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2exzeutxy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qalabexx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2soudndri.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzlroie.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owhpxhsf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkapszv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwbgomp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcwieyp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqhxxdw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgpyrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjpxsex.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgqmyoh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxfpnbf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lruvdnbi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tjekvmia.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmaoffz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwvljxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eahamcrz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtsqxwz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xogpcswt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2leayrejj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2opaluklu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2alcotzgh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhspmhm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cifzqeyt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeibscd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmbnptj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgjlpjq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiowwzc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzniyusx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wslasfat.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyvbhlh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2glfeljvf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgxanlo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fjksbkao.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rshsgojc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lfycheqa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2txppesny.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2asemxlfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prxkqitd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwemhvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itanturq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2beujbtsz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrljdlh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lacqlhxw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwgyvra.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ligpmqjq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bktwzxsu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgwzkzj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ychyidkk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2brelvqlk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cawezseg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ileqdqgg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdraqko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vuggcyqb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvywqzki.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhtyddd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfoxpmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnawxrxp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcfmcyr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avctccyh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrdoep.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjywnrzu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqmlrli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqakgbk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfukexwf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjphgh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcwkjnj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2renjifvg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhynsrld.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2myyfzzfc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfpgdwp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fzltcdkg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdxzafn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwysnqe.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdecjctm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwvcysn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkekpch.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gloyexan.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wazonycy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuetjls.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mduwcqvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stgdkiwo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwlkqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqcdcbp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2imlvvdyl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2utdnzmij.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lunmhzjl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqctrth.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izxahfzl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfzxpgl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iicmfbnw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhvkqnn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjowdfi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdxnluq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiezdyng.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fmayxfpn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oitusmag.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcbwamq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyprfkw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acqwpivz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoiryax.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yltomdns.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiqdqzw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhvghwj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lfulbvnf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyqjade.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2naihaqba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhoyjly.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpmbypw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxllbknu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cokpecqn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcogeguc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oscpeykf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grkhndxf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivremkbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcvqrdc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtknnrtt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyahzzh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbprmcyk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxfybpb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fzanwcrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqxqvvq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpuwsjv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrwjspa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwhfynk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsasrwc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcikzwus.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaenpsf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzlladh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpomig.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjvlfc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vksybked.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqnohqs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtigdgnq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwjvzpx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgdmohy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhtvenk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyekxgc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvoenks.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxpcooq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhcdzkn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jltgfzgy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jhodzkra.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaguyljd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sauedpjr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jowdbsyi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxcaff.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmwrtxg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hglhntkm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zythjsyb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2olbakzcs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bgznxdtz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2berbsllm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kemkyvwr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgggyoj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuseezo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrwixmb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqltpks.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlmojmh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkqlurn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgdxkdd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqeacut.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbqknvc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvphzvc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cyarftaz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrdyiul.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pipfzmjy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkerwhs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xdspdbvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbtclwu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bhizdwmn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2veufwdcb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2puwrxwwr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pltwxdbc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdfuuhz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjolwht.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfqqfbc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gaprqbvg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eictcoml.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isckniea.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsyreno.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqklfuzp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqjqxsh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrficywu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2icetxxgw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahxybeu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zuejsamh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoigbuv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrzngui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoytjwv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qneitofk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqnvuye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpyzofs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfmabhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkpiyvk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ontleuap.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2shtbuden.html


<!-- 参考信息 -->