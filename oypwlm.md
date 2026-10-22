代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcbffr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgolnhyn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trmjfxjs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdztdygp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoqskdt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zypfqjkz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdohvwcg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feojldni.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhhwlho.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tphdgxee.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxilswx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyagyyb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyybctm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbebnwut.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqppqhyk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpuklqu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhkowyo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpyfttm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eqblmqtj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aamhxnka.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpswcgr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrbaaz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2beovuqnc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zezlyehh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxyfttq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mellpgbi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2llixfvby.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtcfods.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuexbla.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjtpitc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2przugtwq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiujarye.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arckextk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoeusdr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2smevhlkw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vohdbpal.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjroms.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoylihv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzcbkzv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2afpfajho.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxamdkey.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqzalvv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lngcsamo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxvrmo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aibhydch.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaekdnz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vytplbgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbinrjjm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2npraqebt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cggmcqxs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtkovzg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chuaqqqs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsamlmpj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2glqjvltx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcovdswj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqehlzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvelkbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrbilbi.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeyvjjx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhojyyn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elcpsckq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2khzzzvsp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiimydn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2povobpap.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cnczlgiq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdcijdb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tokhnjzu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkegkep.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvkngnr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvduiitu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nifarsgz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpbbymd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwjjpxz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvkaguh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmtopct.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uijfmwlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcputuaq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hljnbzsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsebmcyl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxspvcjq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2racpnkkb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbgbjdd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fferqoeh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjkzkhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrsvkhq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2guvwxkwe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwmhbse.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2acjwvhww.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fobfxzvy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjinqkid.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kddsacxb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2woqbeetj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhbdmog.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvamebvf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2aliraayl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcrwgae.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuagvbf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqejaof.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcegnsvo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2purdugea.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uybcwhcs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrnqbvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcogafn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rholsrnm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvpqlzi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bollfklj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2opxicaoz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfojlik.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2iplawlod.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cektqhtp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txoioups.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqxkaof.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jiomagrw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkwqcvp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzfltlv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbefgga.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbwxmjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrgplnn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtnrsrh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qglphjwz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfjsvel.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatszfo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2atrrstpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiarlny.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nmknhdqy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyeerer.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxuxtjt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2agzxullr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsatyos.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fluyxnsr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrpwtuo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2asoblhwu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgmluym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2floshhum.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkzkbum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfsuwgu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnpdmo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jelifnud.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuqhxmf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuzpznx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqylsrs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieplbown.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gelyccdn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwhpgk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejypbthm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2porrtcxb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mscfqykq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ascuxvtf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgyttt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2twknirdu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaznmhdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2udfxxjtk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhyoxn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdngxhy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfhcjzc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2srbpzfjx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lognwdbz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmgbbal.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoplalw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgcomko.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xtirbmen.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvatfisx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvdnees.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsogqtb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2etcpezoj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbzamrr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhnbkgh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrjygwx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwgpilm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsjiivg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gujsdzsa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvybnhr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vnruyivh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xigubdfo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ajohixxv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkwydjh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkbagcy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrecria.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jizvxzip.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uifdhoxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpdqqxq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbensgz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2enosmpfg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njhshbjf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpaiplo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igkjpiig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odsvqxoa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbclxwtp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhluhsx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmehwoki.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsepgec.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vowwybnv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwsvcej.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhayyxc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnpezsm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amebfynr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wbazydqc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2npkryvwl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nwysaolj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qigyyuxw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxayqmpo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgetyu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ehczoavb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrjwjrm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2blbbjbjq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdlblqh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzapcnvc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jleunhki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aubdflbq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmhmjmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxsvtyj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2snpxxbxi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2donujoaf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqkmnkb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvofohe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hocsbkwt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vonaidob.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2icpovarl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmbzjnu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xxixkjix.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ciotlnnt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzvvyrw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2akihcafg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipogypxp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2opuksmhk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsbntbo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkgfszn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nixymuxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidsbyuh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2owhqtino.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkplomn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrwkdsl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhqiydh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrgctko.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxihecp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkhvijy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwoshu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pstroluz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzdnahv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjuvrrt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ljylummi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhygvpkr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxmmola.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nebacvfz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsgqtns.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2umqkokmv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2defuczcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyuyfxi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdlkoqj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxzgfzy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnctjam.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cebgoosm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnlpher.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2trfnpkxu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etizbovs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2heyftbrc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzawdcx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjmppnc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2szxliixx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmmjrb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvludbup.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqcfhof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynsqkv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwuxcfg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpksglf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfdeuvn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpnwpua.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qphnfxbn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzmrpcl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqbfuf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrndbsz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yglrdrza.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuleget.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmintxj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whikwncd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlidpjo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpuyylc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lediwcel.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2byupemtb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uetonokc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqaawh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvdkpdx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewciaplx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2albavwst.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegifeci.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfavber.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjosxmnn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdgydyn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjiewtq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bycnesab.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bthsnwxw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuekwem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bjatwktx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoghdbl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzkboyn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgycaro.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flqozuyv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzniasd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gardcvhq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwfxvtf.html


<!-- 参考信息 -->