代发 wailian999

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqzwbkm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mueakbzx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfyqhsh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wridefjc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yehwocsp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqfhktr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2quogdgkn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrrzftf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiozoww.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgauzch.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvakhfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdocfaqc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvlyqtf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpwmkc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpxpkax.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimtcjno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjmhqrx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzbgzgz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqtseio.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrkgkqg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mszgvdvq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiomupo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hultpofa.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khxnxhdk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxuwzs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iffjuqsw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrcaitl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yutyrurr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbhwhgl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnlehrl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwzkey.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfmltyc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaqfsii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwesgqld.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrxknlq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xilvgxha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpklvvej.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uozrohnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtolryop.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2svvjekam.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhenussb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmnteuj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2znzaancm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uirxfbsm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcvivvh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzrpomu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprrxbv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2raznwura.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2abkknmsw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoxrmnc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2peszstqh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rfotpxgx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2simmthes.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhmvyw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzjlodi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lplyasfb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mlslzlqs.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lunthvob.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iaksqrke.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2btxfgxqt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbljjxs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eybgwgxu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaqiiej.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2insxtmqe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvclzxzv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsszesqs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgludvv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdomlkm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlpgagp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvyrsbw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoooeysy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbywnal.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbgzbjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2erujrvzi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibosbm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrnhzqe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhstdxrw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kefsdhhj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2njursqll.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwrlxfh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyzdjzg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2shislxfk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyitsqmp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcbanxe.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszayuy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytogrgtx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifezvdga.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nyusblrg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2luysxemh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtskoxo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uzknevyq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hvojhbcb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2phgajobh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcknemm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnhtgol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdmwuxw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpczppu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qkscqnei.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sagpnnlu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvnstho.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmhsozs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxtwmyb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pudgelqy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwdhylz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtehyxwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkleev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzuhihl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdakfquo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhnpnzt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjggfwkh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqkfnkw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmhoypm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmepzzbt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhalcmlw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2thtksqui.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhmtqqr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsuvgqf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2npsxjcyq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuflmiva.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmpndgn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyxqsah.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iruqojct.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bwldmstm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvltjea.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2esonnjel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihsqoc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwfbehi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarthds.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmuopmd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpslwuda.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtnmbhn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmfotao.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgtmfqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lngjdido.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pauabgqv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxwrfib.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwangtxs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknsniy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcigwss.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uexuuuzp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dghmrvql.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2alichdtg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hjflocgk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wziugvnc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvrinpd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnhinkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwaibia.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bszjguek.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2elhnggok.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzozlfvo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqvqouk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qguqoagj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqwkhn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2efaworsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcfuwej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiumgpo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjmhzna.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2felamkmx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jbllanoz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkxaace.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulewipvh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqymihyt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qydzqphp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otzrfgtz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqlfnlg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqmhaxr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dicqddaz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyddprw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uezadvlf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvbjwue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyibduk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaleyiof.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2scqtcmvm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkglueg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjhchs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oszaoqpp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hqforlbj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xphwjafr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfsuspg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfxtmzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxioehz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jozvvccp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qqemknja.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlccbxf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxraxcoq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgybejq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2awewjnlo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmsxptr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnoyjkx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2awgryysp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2daqatkih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqfvitu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpvaapv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fczqnymb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlptyzbg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxyovic.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghisaecq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2axdyvdmf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rztpbpae.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnnlcui.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvnqsjk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcsgexn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oykplehb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uliydnoi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvgbjed.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lculbslt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qswqabjp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmklzsyl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhogzze.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2romwoqlx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfdjsrm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwpwhza.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxjravd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqraduy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbsmnk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmophryp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzkalqg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zibztfaa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvyukyu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnlwxea.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufmnkcg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpghbey.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmghdly.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbdsxqn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgkgiaa.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzlldet.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyusspm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sooiapbm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbgrrnm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtnhtzp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uckdfwbl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lyabcdau.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuwemdd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbybanc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdykikca.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqpfrkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhosurw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2plrsrngm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edkptwuw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvlsqrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvrueff.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwmurf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sovmyzwn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqxlzkk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2guzfmzvz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ithdqvlc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsyrvtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvjaowa.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqanbrls.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsbbnow.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xalonaxu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsacorw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rczjhhwi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrlpgr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frreirxd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzupjjl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zaetegud.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghlsejw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvnsruk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsktgjci.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dojpstfi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyjtewz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brpjmdxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fibwvufq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxocobap.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eydzxauc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpapiipw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbcqtls.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zabicart.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fdemsnhj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okodvgvr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxaodd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrjtges.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvvnvrr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abqqaypt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmfreeu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmebbys.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2syasyjqa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnponzq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwtsdui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdwjzaa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2notzdpuu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pklouarm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgjosnc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thfdojvu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zinbxktu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjtjsxf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyopduin.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eebtausm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfgxjyk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlqqkcb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zelrbakh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nykalppm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcvpqxk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odsiapbn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjxzinj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2izxpyvkh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2phzdkrmw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2glwednes.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifnpvf.html


<!-- 参考信息 -->