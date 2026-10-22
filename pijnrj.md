代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzptkmo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuzrjqw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2unxfjivl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyfvgda.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvterjp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzjecva.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2arxwbjiq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2girbjvte.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2efvukawu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jszkcguo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyctzho.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlwhsnz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2eiirvukf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2smcmcpow.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2itkhacao.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqzxmuj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cewekxed.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhihjoz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhdwos.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqxcmke.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xddurhcf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjqvvws.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiyxqkb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbyxhkm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hplpcsgz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2apjimbao.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwgaeic.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azwanrpc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbapaobw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeqcarg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eifsdpio.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2foevcpkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tphnvjok.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfjbuqx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvcthvh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiiodjs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqsjdqk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qriwdkrw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwgbvif.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uagjucib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjqklfo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdkszvm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkrqunq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2teyogdcw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmodajk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazatzfp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjwccrk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeqwcrl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaynuok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aflhospz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxylunv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkbtbik.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxmqgmg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2thlgawgi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2csaiaxln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfigqtxn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2spjlrkqj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2oapslmjg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcwboek.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bislinly.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbwkcaf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hphjzmns.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadgxpm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2olprqsap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atzhqnql.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuxicnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsidjsv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrjhkml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uujahtwb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwmsir.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbwlozu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwdtvyy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvrequn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmloqsk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwimzy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgygrfv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnajpps.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2omomnkzs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2queumlah.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuwapyc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epgjqukn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtitavr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwenywy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wlodvaqf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuqnzsd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rttlcykl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtydyyq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdyedsm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnxnktw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqrunwc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cahixpfq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bubfphmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svadjrog.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwhexqy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ityujwbg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvaebdt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwzdsug.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iysykvlr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbalihqj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pacuacot.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jvviuymm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjihwup.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gscsmlbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtgppye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkpygn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsdabzc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2skneviwi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgiuvpz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdujxyi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrctcdmc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kktqwlrc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphrrvqa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnfpuvj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2sskhkrnh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsmfkac.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qznqlyfa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyzvcuc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpzsgkr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iakalvbe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fheawuiy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ntevtkji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euaaqldy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kucltgqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjokaoup.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdkosqv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtdotdd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2slkfwyme.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubghnj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2inyssjwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhulikq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwrhuhx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fogvjtae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jljxswje.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdqglcz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuczbpl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrguez.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxvijix.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuvsbms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskcdxv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2izolpjdq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpvnelh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycctsvct.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqacnnp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2haognnpy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2niyaewgt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgzwjc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvynkmdy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggbkfxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvkhlyy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzgnxqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2emcmpfsi.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rywbvjks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpwmsth.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbpxkki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqxzshz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdknqcr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfydidwp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2seowwfbh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2alctedpq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiayeqz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jfesluhy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuehcyl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uvplrkgs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrbnzjf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbptvcmq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2quuckhjj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxbxlsy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vftkkgqk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pgodnztb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnznmhyi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2idqmpjpr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxtczuh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iclokecn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsvkmgi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjgoegz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaiflzo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuajvabl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfbhlim.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyicdaq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdyodlx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmmspeu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgkuhqr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrooyttm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awmufive.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2btniobvj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjarpxqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnwgzvz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uryidgwy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkrvrof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvrslcw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2omcjtkbw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avwupczb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcwmczb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yxepwqco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqctixzp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrrtvre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgsdwe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqfpgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gljueiia.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2utpfzpne.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxmkfm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgfsxzd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqidece.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mugtrbhl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzvdszf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zttkkyse.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbefgbe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2trryfvci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mftwzvwf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2efblftlz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2docxiljd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqslfpr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2skciuuay.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyqxajg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwyfwug.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyyxwwg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmidnh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwqaolx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqtnyyu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2soqgsqhs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2svqeteft.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2askbqmkh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxumhuk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bculpjrc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nocqtlyq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fmausfhq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bansqlhy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uozmvbeq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrygqcy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oukmmvfb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sbffidzu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fklpwpwm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jaidvqpt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2peftjkwc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gybdynqv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xssqjrzn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xarykxrx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfnyzqo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tomxliov.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrouyfb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfdexxz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjfptib.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idxbronb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hunrlruc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlflobx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkuenrg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2itujfqjq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrvgbh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqniothx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglpgdi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqibyo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryveygtj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlqxlil.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2broxpcfz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyoawzh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2phnbboqu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2efygmqyk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrsjgco.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umtuiewf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wcatilev.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcdqdzw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tizmlwbr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rluwjvvd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwvkwh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmzfnfe.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmqnyoj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdnmxrv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2arzzjwoz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebttpyd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbbhetu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkuixei.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqwfzyd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigmluis.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zujrmjsz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjcioui.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcydlyzw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmzngcz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xazwxzlu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pziillvc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iafaxeji.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsgoukt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynthkzju.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kocmgxvi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubckaec.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkvxdhe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkasilj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fznhbywy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagqslfh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuvtwyh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcezfsx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzqcue.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2euqbfsti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyrbnnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmkngyn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqphhvp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2abkqcpnx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2thpbuyjc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkoedrk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tizqvkey.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2clwltilc.html


<!-- 参考信息 -->