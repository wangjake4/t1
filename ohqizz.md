代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iboixgeb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywprakwb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadfgprw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jahuhmto.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwvszwh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvpqgg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzgivlx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjsoyjt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzglfls.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbxrshq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvkitda.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wdujhykv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzvartw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwxbkae.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvfhftr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuaitwo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrgzifa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogtcmlu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtnmelr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjabiex.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ytonabiu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2oftepnnl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzqpbr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcldvwha.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopewwcr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2glqjslhm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgyrkip.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvylfl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcuysq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtmojxf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhnbnbp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zejszaiu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcbjii.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwohhma.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkispct.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqntwrql.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2etiuhkzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqnciok.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdatpru.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eenehcwc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2eklafijn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gysyphyw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nblsypjw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpipijkh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmdjahy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqdmws.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvbvkfc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwousvlp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvtgtfj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgesbojq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfsnpvo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wierurjx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpbtlxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkttzspx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdafzix.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jkosoynu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaamnui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nroonboz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsrkjpi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ablceohr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjhpztk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eophmwqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsdosiu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bljysfvm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pehncyjj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrigsvi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdlkdmo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kapykyrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omsormey.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsligvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnqelhb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yusdrzgs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdyhanz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzouqxun.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2doycpcix.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wasjrimb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrzcvrj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2aczvqnog.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfxqhy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2twltjbsn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tupjkejq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlrwnvo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oeozpdad.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhqijbq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2goaucths.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxihujhm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqukbcfo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ustjmtfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjyyufw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuwkhgo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frzccows.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wpafokrk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkcfwgk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yxphusbr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqskwbwc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxrbtk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlechkra.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntmdnvo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlwdnyj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wermskgf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2enhhuttz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxosvxor.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlhkydn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbkthka.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgubgke.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rmocrawh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gumxzqgn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lohcctwz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrcymsg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2goekbedq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2noqogtqc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvtrrxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcifjomr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvbxhuo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjathghh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2giiutpcq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzoudki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyonkfd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvioqyrk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sngylyls.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2broeissb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzdcie.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzeaonq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2abevdvfa.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tammijgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zukvbqgt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmzqiif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvebhdpe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cadgcahf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeurpcu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wstxqeib.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsmilgb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2imkrfdll.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2amfniopc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpvsqvz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqncae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdzgwtj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqaknhd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2umhthyyn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2amglkwcf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qfizkyhz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrddkpo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqyrkw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrncqop.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcupgdh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2npgkvmsg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xomrfope.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuiiaxv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2txkukrbt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2metuawbv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyctjbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjprfnco.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bieycfxv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqtckft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuxtukv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iptgcsum.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dujgmywg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnfmyif.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2equdhrpw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxvmonq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygevbdvj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutdrthj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2etfejlmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnayuhl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfqsngm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrkebjq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbieavx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhnwyli.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfmqosm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhgtfne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2typnnvbx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2oqevyfzt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zizdyjzd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2luebturb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkiubi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfivbwn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2msfoolnd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuxnioo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lldzrqzw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhhlfoj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohynhtcn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsrbhkq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnuembt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nskcgdiw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmobbmz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbaecyo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mchgoukj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwtkzhb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2othmsrqi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvtktbz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoehzpm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcscxzg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwomqzlc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyckwrei.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2spxphucc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnfrsda.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmibwmbz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnjodeb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuefash.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbecemj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cohikmxy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwhlwrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrrhjmb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyryxmi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2svbyjflo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqoufpu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwwyrki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cadtsrre.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhipsz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2scebkifm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwhznmp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mqifhjbf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqyowzf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzgxfxw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeyhdbv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqzttvi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfhalug.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtlrpb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqyaxuq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khtdfmzs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzmiwsr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmpfwbk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sutkndmy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2khjqvyfr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcjoqgt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlbbpio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkytgyvx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2echgqhvb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2khiprgva.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2giskasha.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfgafko.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ulidyhxr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmklvlf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2widdltjx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbebqxm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wttciftp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxsospo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fboriiui.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2exovnmkp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgmbkid.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbjxqvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnilrxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zerqvyak.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hkehtmii.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtxjaig.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wufjfuqp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkoysva.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxqwctx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgcevgt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoqblix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvudxqiz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ttofdgip.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2acptyytm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzvpiym.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pclzajjw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2spmweerj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxhxus.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nworzflr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2apmywjqe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ykduvfwp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgipnez.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiawqsp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlvrjph.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzsjuel.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyvcexz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2djremhlf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlyispf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2peztmdxs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfifnjg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2trionglz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwtpsdy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipltjgej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lceuttzk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bymrfxpu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pocyheoa.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rsadtigd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrfqlrt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxjbqzb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakajrsu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zknjyvaw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2neuolekz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhagtd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbklhix.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmrjcca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuqacms.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfsvpdd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2slhghbld.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgjmlyw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrqldak.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeexxnu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpuxsjt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xatxkwne.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkepjymq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shkcrrjy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrxyfg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeogljl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfqzwym.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eycfbvbx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxidjxj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gaynxkot.html


<!-- 参考信息 -->