代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjdjmrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqytdbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pevwmgtg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjqmnfq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbnvqxr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgssbap.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2otmfweqg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxlrzsa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2upplarrm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2predtcfc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxyeydp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sejhoepg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kkskazae.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yibszcea.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvkeqwp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxxjhlz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2txbilryt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdwrmdz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtunqnx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jixthvrf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhxgqnj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyoxztv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qhslcuxz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2prhobsvt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shfzlcif.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hefqxjxr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaackis.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpouikz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2igysrulp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yundtnaa.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vucauknt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nirnzhps.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjavtktp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grzmxjmx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhogqi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkaukk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbxcymu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nptpwoig.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmwvbgv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnlmcvv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtdoauz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhnbdlt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwharwyh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vckeeple.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2myaoctim.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2budtdivk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enndkreo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2muczfnjl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglbvyjn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uswjmvdd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwwdzhj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hpokubar.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scjkzaah.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eoavehfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xchgcleg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zzftfbcu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbqowaf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdgddp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cizvptku.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llzrjhrz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2txnfjtiv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaebktk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2idzbbagt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhmidgt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpbwgtk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcywlbu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzxwdbb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdeqlxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gncpfegn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hfopgafc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjmfhkw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwwxkm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzldwbi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rajvoolc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2laiimoio.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kuivrwvu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2drerotik.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjsrdjf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rddhdoaa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2urhfbgrw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iftkjoca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhbipl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2futjrxsh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tadowpke.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgyjcml.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fniozyox.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2txgaiukw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2refeenvb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyzeznn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2quuawfbi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmtdoah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sahznwlx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2athlyckz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqazgio.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awimfqvg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqapkezh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrbvqyu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggrxtk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2awnyrcxc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwsucmx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vclleiwr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfenrqw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2himkxzvo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2duzdladj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxzdvpb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxdskyx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2viyalfgs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjsiyhs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrdwgax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqrpkwa.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoqilbo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcndsqu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yavvlpyi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjcpjek.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwfutm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifsfvi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2flnqyfvr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzapsfb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjpzcay.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnnwpoa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rsomaaiu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyhoipi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhbljv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjxcseb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vwukssok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lidutdnk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uetypcef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuveiso.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2drztypey.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ashtkibp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhgpvwl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iihawtoe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsxuiyd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kigwqtng.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzyefrp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqcitja.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrvtwru.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkvhtob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdmkjge.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdisxhb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bryechel.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkukii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazzzxa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvikevl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbimsvq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpekdgv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2punqnefz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmbgfms.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2riampjqo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qspevutk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbfghwa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfuenqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpzxbdv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbvsozc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2orbbjcgn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjekeas.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlcxeay.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lshjcswh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsktliaj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwxkyan.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoagalfb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnyzhqc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmdpqjn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fliebuuv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2auavnhuv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjfuxsr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwhtegl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcazkpz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsodjtm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzyqswx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdxlhyk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uaflinkd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nzorelkm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzlette.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2schexwmx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozelttxm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrdovxh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ravhhdon.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zubrnycf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fslzdzxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrswlmua.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izduyhax.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzhktg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bdegflas.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntephjas.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxyokdw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcivkofm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscdysj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2asvdeumn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeghkxq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzcorsz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gpicawzq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcuxhek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owahnksp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkbbafk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfatewz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgncmad.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdhzbzu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lubzjsyg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mkausflh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtxhwcg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2psinofbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjponim.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2khobsont.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qyifwlok.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwmoots.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsibzpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hriqiqwf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnatbzt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtcxrwn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkluxaaw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxreoj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbenyokk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mpexfryo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yscunuea.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwirgdyl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmdshht.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2azssfcxf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieapuoiv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtkdqpd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkhoimm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzbimq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hauavqdd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wscjbtlk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxqidyh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkofvez.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqzitnl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhwopmi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqamxbnh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pzruhwbk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2psqaerzh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2etpguneh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtdnjhg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxxfio.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2heprnohq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhmbmnd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jzskflgs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahshlxhe.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxduzpf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnlfgvw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2posronpe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yejvdzpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cevknuvz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jepujxcl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpubycbm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmptczvh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhbttbg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onzdonis.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drgfvtjs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2unffbtfc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqothrg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jznyzqwz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxncjre.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbkqaod.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkezppsm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qkofevuz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmauydr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sywlnlyb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbgcsn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnlwjkz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjomhpno.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2peveimsl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rblbhrfr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mirflfmm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrgxjh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zolxotck.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwrjxyl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvswkar.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyrcbhs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dybxtdey.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlligbvp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kesrcgbv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asviuygz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2furcsvyh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdolstlj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqcxngk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiqpjtx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvqluwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjtrlhz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwscgvf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvvpqho.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxmhsic.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuawsve.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ionreyfy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaktapk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehvrzrq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrhgxyk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxicosdv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhgaouq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzowxfd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfhgzbl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjukhib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iijpfkae.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbwpgjh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxbdhlr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhdcrae.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2limtnepb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xitpzvxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaeudhf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvrkaaq.html


<!-- 参考信息 -->