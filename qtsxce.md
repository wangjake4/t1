代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpesvqha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhqyhto.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyateyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqewgemh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiitbnx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqrdyic.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokfewrt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfapfiaj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaqdqoh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nybkfdkv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyphjaf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upaolwro.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkpdodv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2znqpchdp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoxdave.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pofemcde.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxwvjhs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfabaqzk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmapsmlr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxkiviq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2scnwemfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2juoqrnwb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cimxijsn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwrimjw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gupbgrus.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wylnfpql.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoucigl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxwcikv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilfcsv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzukzrd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsacvrp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lgijisbd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sazckeoq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lehlwpjh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2aduplatd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsapzyhd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfqlkne.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxabhxk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aracypzp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvffbd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xieyyvgk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2avztfnsb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hskgvxyi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2axdoqhwf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rklydfbh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awrgnbek.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lgexsbga.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhusfzr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxivsbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cayowywc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qcovtsto.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiutnuq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gixqvtmr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vpljphzz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2alaumymo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnaqnnv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaalrbtl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvqmuap.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sesgsnfu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmzaanq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmabmpyo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlymyjik.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orlivfqq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zepcghdu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdhtevi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2snxyfbjm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxtpxsi.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrrtapl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtomfgm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhspwae.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2shhirmhc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxotmcj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdylptk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnckykz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqzcpsu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2unjhhaot.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsarrmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrffoogh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwikrok.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2deirpitk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmnfcio.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxsdjxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyhopwa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtghsjr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2olnktqzu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwksfkh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxdkmdk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aecoqrbr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxtprmu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2driozzio.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpjulpe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeqtcnh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bksbizen.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mixtrmnp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ruclklhs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrwrbve.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkeozlv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2strcavkq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbsykqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xpswwptj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bjomkcto.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvkoup.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2geafucji.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hngbdvwl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nodxuyus.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fyinvmtb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjxulpo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2timzcerm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2issmihct.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfserkrh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kxswjssv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsqlkpj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnesokk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llokclhm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtdjuxp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnbljrx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqqqdu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gojqotif.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwttejw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxmzmsa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gphanlid.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeratxc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvvotte.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvskbvms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvuybmk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhhtxje.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcitdgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzamuqyy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hijjgeuo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsuwquw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2akpvznpv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqesxsu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfqpvuh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmagayc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mkefdoop.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tjllhctq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnuvex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcsjbky.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjedmvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzobzgxj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hlshvsvt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfkfxy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iboncaqg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oevkzada.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2grpmewzj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2juzwflph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aufnktlo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsoxkxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwvxsgu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ghopshfy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkqqgfo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpwkpr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yupkjbws.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpziwkom.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwrjprg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbhqhg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqgaetd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtgehto.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bolejcfs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeuqhdc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzxhggb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2quxdkgdz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwmasec.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnqhtnm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnftcjn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragokvar.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafdajd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqzityg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeqawca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzeausu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkzwzag.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lywzeygl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxsdxab.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolciwrz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2btsxkkhc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2igccvzwg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoadlgj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkbsatn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmllvnw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fchpfxqs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2faopgdmt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkwxkvr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbxalpl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bttrxtfd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2njvusluk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjtsjrc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlqmtjj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqvkysg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iekfzrnw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqpvhti.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoanqwy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udqreeft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvgtlpy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqumnwyw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxxfcav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvysncb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbmyywm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umatidnq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twmcwhpl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymujkaii.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gdovyyzu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fohtgvzr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxaqygn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcucxaq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiddnyo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2opvtozut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaalbaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoouyqz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2emncmdpw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rucfwfhk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxsmyyb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2etcljudi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzszcjhd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxseygu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rorufhfx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqubbmam.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdagfzf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2klmtwodk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzidsefi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuddwne.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bgstjlvj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2edruujcu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcbwipp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2khawqukq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jrluunhs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhviaemr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fjloyyjy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnpkdzo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmpkwh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgllxbum.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2orlfpfnm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmldcwyi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdkemqh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpghzmo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjvcspm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkvotme.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzdsiwu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxffgykk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2geytvuvr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgokbru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkewhdl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enkisltj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxprlj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeedomh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkvephn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgbogcd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbcsdfy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzqmfuv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hiatxpxp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxroumwr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2skcnilgr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qigrcmks.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuslznnd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzpmzst.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hugebktv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ahepbauu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqojdwdv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hytsturt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clbbupdl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnwvrsb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdgevte.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdhwfkv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2caejdtyd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2czuzrjoi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtrxbbr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2duqfewez.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeitdih.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoqvsum.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbablair.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgvoial.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbybspdc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vqetdobe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aggsvsoo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmcbblo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jieiiqjy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rncvscsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxcmhsc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbxcsnv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baqxchzq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioegpdqj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgbgida.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dowvlezg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbjmyax.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxchpxot.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yixvurnk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mktvgwoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lszwdjko.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yevaqwuz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjuefoh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2akmodqvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdawzgeg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2abuvuvxv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzxzyfx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpixxlm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfgxmga.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2crqlftbz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjhfact.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkgwvwq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xetmbtxa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmejoiqq.html


<!-- 参考信息 -->