代发 wailian999

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awoohqgf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2etfsxcpb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2msxbkmsk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdfqigg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtzbhna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2avfcbylx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lypzbjie.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyssrxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxtqenj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nafwxbaj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhthqgfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmrcbzl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfzhzuq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwgsqbb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogiyqgc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvsdzv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqdgdb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfjcwmo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwakykba.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2okiqhefi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sluvrvxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhswcms.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjtrfmg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2znjoluam.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwosesl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxpdhn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbevfcds.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eavsfili.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkbihhs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2htkjzlsi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxsvkgc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrftibin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cbljfuys.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2itpdsmfi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2urczgihr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmbcdxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgknocs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xoukfnih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okpkemmm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrquwyw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjwtxsm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxvalqm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfyayzh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnxfizq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykedxdgi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdehxibn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyvnkog.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwewwxta.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcethnc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfltfwh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sockjhtp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jzydyvtb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uybgqawt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcicwxv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgujuwyn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2omnhutmc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mltqfaro.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjgbqyv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjtucj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mxousqty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsvsglu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fpawvkcv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyoiorx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2oukdupzl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlcchtq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eafiwvcn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmyzup.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmobqsi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidpmsc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgqikag.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoysiun.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dazniczr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wychbhud.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzyznpm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzsqoba.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjrwerw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkvuazg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnddllq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacnyeal.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyexyjh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlgnktq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrbjlim.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkdawim.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibxgdoq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwapoba.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vujiyhzq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrhxjaj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjgyfks.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkgntuu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkmlwjh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uslkzero.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cohsdtdj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgxkwah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyawcfyj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awxebevg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgmsxej.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmfbzcz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhqwgjv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgnqbaf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwrdfml.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2btxbtsso.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdlnenr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2utlmhwqj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfbcjlc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsaqozz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgxoawp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tynfiabx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfrjgoj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2brjslgpv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrjqan.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzndzzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2odrxateg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetxqqey.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2usmejerk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaufxyfk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkdznfj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgszafl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbfqhg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuaabjj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqweenzu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiifbbs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzgaebz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yswuehdk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpsksup.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbpmuws.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsgpuil.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mneypgcp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjqbjx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2axiazscv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sewzrlye.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kmthisjj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhovnfad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvohlyh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbqeyrl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ubabekvz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2guzedhwj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnvhzei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lorsnavc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtofpcp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhghdyqm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2edpnxvml.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxaenqv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cnehvrzf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blgnlbzm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vepqtwlq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuiigcr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwmhlpc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnjtphu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzwvhju.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apksplfp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbsdgjx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fbccymry.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igtdytyw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iibtowgj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyomjqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabudlb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkdwnnu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hxriyvao.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2opdwhrbu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihsqns.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkczkntd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzydvre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgjujmh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2heaqqmqs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2acuqcegk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnadnlt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakmsdzw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2reguasie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikylyaia.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoihdfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryduyyrh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ekatrrik.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmerlvq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vadxapvk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlmtwku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nijabifj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnyyqkt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfmknqw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlclhgjj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rayzrsbo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2axhavbwd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuhklcd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgrmbtj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuxshhq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnwrmjm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvlzdhi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xczdrhmr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmdaxrs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrkesar.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2htadinjv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnejkrb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcetkqb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2icepxrvv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2leeyrapp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonuhpvh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkfltcz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2klymeuvu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rimpdxve.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqkatrm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2skwggmam.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbsnqpj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxjmplt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdudybf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2glpzhcbt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2huphentt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdchfa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dktwxanv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzitppc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2orbezsct.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2btjroeku.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcnvhnm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavbcio.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaqtqxg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvhfdta.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcnlupn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqscqo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iomurpiz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fefknhlw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cohgqlzu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiagpqf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2evyidsai.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbopmco.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwgeeew.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqvkjb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtfgsbc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhmawhh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhxodwr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjuheij.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxmxlim.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2szvgghyw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzmqhik.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wntbrqxy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dxerrqbf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvxcicz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtbzmnf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsydesql.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bagybvyj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdjgqu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cysxwbtz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2goumggct.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxdwrvv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nevhozqw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsvcosv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jblvlbgb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwvpttr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kumtpirh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxauudhc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyktjyb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlweapzl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcljful.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdoacsv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrdvlvj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvodbws.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxuiqwz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbxrxsq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaecfghj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosyvuo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clhyezil.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyhvefd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqixaoas.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpyavug.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htfylhag.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgtfkki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2czmiysls.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvqxubp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2smiwaujl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfuivca.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfeouvi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cloctsqo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtccjyzn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrjmedh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmdcgsn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2btkydzly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvngbr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wicvgybu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wejkcikp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fplgblpi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xciqfffm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmawizm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfjxrxy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlafqis.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlvalkj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqmgqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnsmsrt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgafwbi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2raeoojcc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iigeijjr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaezmzb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmhkdgk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoddvmw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xivimfeq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlqcxqz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiapzzg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqsvuau.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqyidwj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeaxfca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbboqz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2abhbwest.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagczlcc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvgfids.html


<!-- 参考信息 -->