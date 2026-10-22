代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vktstpwm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pccyhnrh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kyysqwgw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzbxzrh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqgxcar.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vezdyqus.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzpxrgi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdsygtf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhvyahy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmflgdm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiibzep.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzexrjsq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvjakfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rikjkbke.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jkumthez.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jckbbitf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwpxlai.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuxhtko.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkegxgp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgzrueo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxbeytw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmjowrp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbyiodi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndcbffe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkfzhiy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclhnwvk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpqbuie.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lyssjaqu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlvnwyb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdcqddz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqtbqgb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvdrlxn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoumkag.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxtqcf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaauabj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsptkbn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhiicxi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhmcgmm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2klbxwbpb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2refgrimg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlpzhl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmruka.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjbbxfx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqyiaoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuehqgp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bitdtxtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjpbjay.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nspkinzz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wihljdnc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drhxsktw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvhqey.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2meihbszn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgpdceh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrzeojj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2usfvdbbn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdpufhu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2beigvsbt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzbtvoh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbxwvda.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkizvir.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnmtsov.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkseuwy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2eteftldn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmsilsc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcscndb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dwscuqzo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzqzxmf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfupufh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2msgffmgg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoramcw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgstzkj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgguqxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazunfob.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzmvlkx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2szzebrdt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbamrumd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkmsckd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsvpld.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyvmhwj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyszyff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqrmocr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxwvtb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlraezvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqvzbqk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppsohkm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwutlwp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwmvjrd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2foucnslk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgbjcql.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvyfwd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhddpnpc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoequce.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bojttxci.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqirdft.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzzxzhm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2flfczxul.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfxowjf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xenxdnfe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2slflfran.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2naxgdrhg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynxgov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjkutnf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2deayunyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaqrdiy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mratlvvw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhwrtgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ridsqnot.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwvmmkr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjroqtvh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsntsqi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhvsdp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uezzgdym.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxqbaf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yrorodhy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvryvby.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2heushher.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bjafilqw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2efwswvek.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrchqupc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmsycil.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfsnkdy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2udwvgntq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npmteziw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiycdywj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzhzaax.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgentoj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdnhqrx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdelqrfn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdczdat.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbdrdgk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhovqst.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uuidxvbw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rutoevkz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtdixyl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2izeicaiy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrdgkkq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzvgyod.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnvjfrt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjbkdse.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmeimhg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsczzn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrkzrmm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgptbvu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2edioecam.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmnsqgq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ssipuobe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfxisqq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojplwnma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wrauzqvz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxctmra.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2onixmzgy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnwcwqk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2edddvfbt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rddhqmsw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omnnwxgs.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwidpytv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqdllv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyatgsg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqcvaoq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lenzeftu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjpgwbg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbzyvga.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssznegbo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezktzvyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfxgfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xldswolp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbhpwj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrqapwg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2liemhrck.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yocwsznl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpxqnvf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yglxxwuo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvbupao.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhnmtht.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2apkvuspf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqekcyfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stjgzrkf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxluuvql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgtkmdu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuchuton.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqyznuo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrwbvlb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoevktu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xinpkwmg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsbnvjb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vblsvjpe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rattzfuw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkfhvca.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqybjqfs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfohlddk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mymzxyoh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdeisww.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyucpyhp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wveejuyw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszjlobv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoemkcxl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2chlzjzzv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqnxbzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vueavwpj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2suknomdm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfkcszo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnobnrzp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdodcoxq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2clnpftml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nefrgybt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdanfnb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2akueywap.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hhijntid.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjsdtfh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuofxxs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xnojvklv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sgchomzy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yofhcyfa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqcqaxh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ospdkrpg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqgzogf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cylpcnxj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vwflvlxb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhrgeuo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2asfddsnu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tidcqgmm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2chhhnhgc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfvlko.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amlnlqcm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgtuokb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsahokj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfnwkai.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkttsly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dijvtfzk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2meinzyti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfygdmt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzarmkh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoddhwr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cusajqgz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fswvotjk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpfkbsi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2atzgmhdk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kahioltw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toqdqkbi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2htytoesm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhhlzkh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2evxtdxto.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrswdhk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnqoqqk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqmcync.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwslgly.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rohzawlv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iipcsolg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aowlrfst.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nheedkmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhrcgri.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2chemtdsr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxzwuqv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swccpkqt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjggprtm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhjrzsj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqvrylc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirgaml.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjijjcgb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kzetcymk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkmhnkn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxjhaxc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsaqzvx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfzzoqk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygqxxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihhfehs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zghzmdjr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xymrwmla.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmfxzzp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xouvkulj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2afosqqbh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2slepwxla.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2erzvatcb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnytcan.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhdsjoh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmtoaul.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lmslmixk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpiytbx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yymdjfvt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lmttxlcn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2joapchrm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhsywlu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkskigi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzjqbbn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuauarw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoihtul.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkmneku.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdcmlnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuptbug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2morwmmju.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfckner.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqabeet.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxmofik.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmtuugg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuimzfz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2elmxwdob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqtbmva.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpevqjzz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcprwppd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2itoyctyq.html


<!-- 参考信息 -->