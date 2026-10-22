代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jleyseqa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaynalzy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypolwoiy.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcnqczb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevvlgzf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wutuaolc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2inetpizq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwgstif.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqwjggz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2esiyqjna.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtljtalo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2reotorjs.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2koadribs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgmpdzw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwglugzy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gzojbpzz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2uciukogs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyywostv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eirnvtnt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrmgipb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkisgpi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzthhhj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaetbtb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2goawlbzo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yescfjis.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdrpxih.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfrykpb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kaomtnpf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtqnyiy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtbklty.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqinwsz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kazddurp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuqoqse.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2siyyjmvy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyxxtft.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpeoaak.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xujctfld.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uucvecou.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfunqv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsanwth.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxawkbaf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvztykq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqurwnr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmloewt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqhmyvj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkowizrx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sswvcmbk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfskhwm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqoppzz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeqxzzg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbvfqb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzzgjxq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xglgzlol.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhznyya.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2biqabyqo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nshikhgx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpuyrro.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tykrmxal.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhewzpm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gekikksj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2aewxzoqj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwsqxji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bprssyyf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2chywcvca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2saewrodm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnnfasf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lioijunk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvtadjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojekcexx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmjidby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abjaiidx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzholhk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qslcsaae.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidehjv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbanbmr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbohekj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2klaebilh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2awoirdbd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctychhvo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mwssuqpf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxybuvsv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlkjrdp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzjhlhj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvafuxn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2talyecfu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxipdpz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdetlcml.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmjvkfw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xsginbvi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fpktqqlj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2znlwiuej.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsqfjir.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2geqmammo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nckueugu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyscdqvc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aliiwjij.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlfjjmf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdauipfr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnvoscm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzaeduh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bprqtsjw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzzhlqw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnithkd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fbernguj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyjzkgm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfdfmom.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuzcjzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxtxipz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxfszif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwvvecg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscwhhvp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yomiukmn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiowmqys.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2atxlozee.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrblara.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxeevz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kodpxsos.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlwzlsp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebvbfn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2okwqpdrg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lclrvcor.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lbghhhrv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qzesbclr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmmckod.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zouxgzur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkdpti.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhjgpwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjamcd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzabccn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2potetzcs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ojudmkko.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeuxwja.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeidwqgw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2khqohopn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnklliu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzawtst.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlevzjti.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lnozkvrk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlooxjdp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuqevof.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2idqheugy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdzikgr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyapiqn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbyyyxr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnaikvh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrfcuxu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxldhan.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjqglrl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lonsfkri.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzexibjr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqqvlkv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjvvaym.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqeehcw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fczvarik.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2winyxiao.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqyujfu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqeklhh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdgluvy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlvftjs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebnfuq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvptlg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqufmlgu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdoyqk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zexawurs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mezbqlbl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpnetnl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwtbgdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vgetswai.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nelfgzpf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfsjpjj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjsjrfk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2abecollc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wzihksva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzkfdw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qynvjjzz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvhkrli.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnayqwe.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xznbbpud.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdkmfke.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqbffyv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrgytrh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgffmaw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrfagnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wudlxrap.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxiqhqj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lktogzoz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eijfjkvt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goyayqpb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnvijdu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pugiwmss.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nxofuykl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2avhskxdq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxjkezm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2esoafybm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2stgcrtqu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizmhuw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2abtxhuzg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnheeqa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgechnd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2culnjega.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynirxpmo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsxvczo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiweytrr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpdwjqf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jpttgfai.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvqrvcf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbkpqkh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2npubpqgx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kkduwsmu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjakzql.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2shnzzkmy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2otcajhoc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2omrhzwja.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtdkgnl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2npdafgre.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwfbikt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqgncgr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjjpnxc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbqkjej.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnlzcaf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2npimvwbg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xakxgbpe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwhzpe.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2npkaxoik.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuroiix.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeujzcrs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvytrexg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxnddca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmqdqnn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yujmwlfq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucldpgvq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nstxbysr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2agytzznp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojntmpfq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmlfwfc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkgbxu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdzlrdf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2monmeidx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsruqoy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvvbrn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndalguix.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzthbymm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvqqdke.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lopzroft.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbakjyhj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2scmsxxyr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabvpovg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqaudzz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndehfepc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwseghu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecllnlon.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdndapzo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2thrsuhqa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjqlhi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jskcwtqt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwkggwn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gytiezak.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caeddfzv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2soihyjzj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhvlbug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkppjnm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmdxhsc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqipkif.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jkflwuih.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2enmxrrgr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zealhqxe.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nevmazhm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dosyuztc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arckrnnw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nggcoqbn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekemwrpm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2etneoqlc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlqdhks.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2brfkdkka.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfronjws.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2grcnldzf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvqfbi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyngmuzs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiusfwph.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qebkftai.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qutscjlr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwvqyvj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ftewbfnh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fanpzklz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fipivptg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkiyhxc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmfgsqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwhmkxh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvgheod.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tednupyd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkcquao.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtpwhfd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmdediq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lujgotaf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jutvzngd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnkcljj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqvniso.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjprgfys.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuyrai.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqvliag.html


<!-- 参考信息 -->