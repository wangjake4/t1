代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2svaiiuxu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylactjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkgcjtv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xgafzugs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgdklxd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fbexncgd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2topsrypo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrssxbnz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyzckbw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzjawmm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nunvihhc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhwmbig.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwqjqpz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oftlnggu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzuxth.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tstqyvwf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxsxtwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xohntaep.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuayigd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyvtzgz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtfnhas.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgepwyna.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kujzldlq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stazwqcy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpsntyw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pymexzir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2whzfcuoo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvshjee.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapyrpvp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdernxu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqndidsu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpneizl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdentgch.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jycwtzas.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2frouyhxk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmuwaow.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzzpgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpndxrfi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftduqgwh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qotwtrbm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ljihgapn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yosvnsxl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoegoju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxwhzmo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdewlhy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjpulhr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hctxvjmx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfzpvzf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqvfhgi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnclcmf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxxudsu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmhfxwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqquvyjg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2scttdmer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjywusvi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fthaxraa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbbqeil.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2silauuno.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zjklnrhf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgkeif.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfojvrxg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufutcrty.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpnteau.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gomumnjh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2axugjxga.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rajbgpgh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2scinhukv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2grdbdenr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sfncyiuu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtyvwie.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxjzphg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjrlnum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmljnqp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2eygrernr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuidylyr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mleeaark.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdeqfmc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqxtlm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcemnhr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklepfoz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuegrvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dobrppof.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkmsvtw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqyktw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nempphfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsllizv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwytxwa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fpumzxdd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoxptzd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fxenwnvs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvreskq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcersno.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2afomnujf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyccwal.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mquybahp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2doghfjir.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdcdgyi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgtnsev.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hurddzeq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhslsms.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ggueuikr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bunaqrev.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwzeadg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vlacmqrg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpddmul.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2knmvlxlq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cfymiwua.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgkfasb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gokxphnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igintlkq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaftory.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuttsic.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eoasjyan.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eshnjurc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hufwqxqd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2slewbvww.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmopudjn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eobsanjo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmjkak.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2egvyuffx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qycrnobl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgybzdc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxjdybz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsplxqu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcrtlgb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2icfbqfvs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuampvha.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwzihvm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvnbsub.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwznrcqg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtmevcp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjyfzj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnauecv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tirnrims.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjetvmvq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupswezz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytirrryj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2joajexks.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnsmhuk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2buzeofds.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjqqbmv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdoutrw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cntlfbwz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oeumfgds.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cahqejnd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnycxpiv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcvaynx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrxgern.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nayhvnrj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnobiuo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzuvqxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfkbutn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoztsyrn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tzperbar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsorhyqs.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wblzzdsg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmlllkn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeozqwe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrowzwu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krcjasaw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gkebplpc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epapjogk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpvhusg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dryjjksf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcznbbc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsfyxif.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbuomgl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlsnmyw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmnrjuv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfemqymm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqbctbp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbukxu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdnzpha.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbvpdhx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2binfmbwx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqjtkik.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfemhvh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbaeopa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qissttpr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dveukxaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2socnsqab.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aommtoot.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2asuhezes.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ytysghrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwjfeew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhevyhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkzmvng.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlnipfz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yimsiyzi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhgnjyg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvlcwjz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjdjvyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uojzwjll.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiagkcg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhposvx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeqhfrz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgitscw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bezadgao.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fecuynph.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vedbvncq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcrdhsv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfndrld.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvxizux.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mghnioou.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtxadxy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sppouwhn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrfhehr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjabhod.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgkfozt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlowqvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkykdlv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxobxpnu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2udhlglfl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvaqphf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2emzjvbrz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xgieucrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxykyr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqngeog.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaupore.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lribvzie.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cwljaaqi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxyafub.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hszzotuk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzmvvez.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dybpolmf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gehbalxg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cglclmrn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbnwcmc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrngysqa.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzljktbu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwqtipc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmmahop.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtavguf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pybgrfwe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tiktxctl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyfrjal.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhkajwg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbptmvr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yelqmzve.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtextqa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylegrzss.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnlwnoj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpzemb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vapctmxr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajchufwz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oamljyng.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfrmrvc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2caifhqqd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrpqmfh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tizzzzig.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhkyezb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2czugaslf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neplxfol.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrvqmbu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ridbjecj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyulboxf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbmeqmn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yttexyjg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvudrnjq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2utwvilod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzzmjbq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxmejc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rktmmvwl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2glibocif.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeqmzrq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtkvbpd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qvudfstt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nodkjrvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2npzenogq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuubmgk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsbxtnt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjnzuav.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgdqoqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfueuvsy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnoclwr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuquzhku.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwphau.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jblysfzb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2irksfhfa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tbezxjaq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqvbkbq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2noggtngq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vilqrplv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pkilfmqg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2acizaacp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpvrrwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvoftyu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxovfb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vfttwwrx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqgblls.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wubvwlrb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wppxsqlf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjwdqep.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuitcwk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiwodpc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoqvhvl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cjctqzum.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2laccymdt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ryehwyea.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2apleyetl.html


<!-- 参考信息 -->