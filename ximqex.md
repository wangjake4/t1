代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obducaum.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcbdrkb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrglduu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvmigwu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiahdll.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fssllpmv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhielyv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoayofe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aegmukxo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fobirqmp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dwudwizj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqrsqll.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cogbdpil.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmurwkds.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqjgjmu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkwwnmy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuaagln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzneelak.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wokzyqar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyrhdfp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawgquvh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuadymu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmxqryg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjtlcq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhrgkp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdlmutx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcnlled.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbleftur.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpjqpef.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dlznaduq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlwetbv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbijkkfl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qohouzwp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbccphcg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhuybce.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sttwrqjs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rkplrbrw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brajbjsu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iufqlthj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgscrrkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wesgysav.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yaetzwfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jecevxuz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtlckxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgylqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klcvojmr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2inziosqx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyvfxva.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoqkzls.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tanrkbti.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieafcraq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2usxbrfbk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeslbsk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmgseuc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ibujzekl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2efscqxrn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqgniix.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zndgvthm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnahpxp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ufawlvqr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xpimawij.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tovuulxf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zajwjrph.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpuyuzl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jksegean.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2upoarmmk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uotsxtqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkhazpm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dufpzufv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbigruv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbnnlto.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuhwckf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhlkind.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cchclzuj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwlighy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcfavad.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lltwzszu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxwphjc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbixmxwm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvqzsc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrjpkry.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvnupl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckbesxo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjwkzvc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tynowvic.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2npqkmikb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzoghi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brunssxq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iabtcsmb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2eenpsrqh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdtflew.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzhqiwo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxkyfy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnrznfi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtgmaze.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2igalgjfz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrjpbvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiazrjbc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqigkdqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vusafjwu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjiidb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nbadohxn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwkznbp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mawboala.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsamuyyn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjddndz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gowrgamb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzaqzmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2laemyhia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cajysiug.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mszigdeb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvqrsau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cspnbkwa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2acebfwca.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wospenyw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bshrhjyw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykudrvqi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcytrod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bupyefpo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2znefvlbq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoqwujt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovnscjw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpmyqct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwppjpi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkimlxb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqaplqp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2idyrqaiy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvontqmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2exmcnsfe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gurwprjr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mttdlyju.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kovdvvcm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcwrsat.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsznbixs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oxujjiqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eigxpmvq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqdwlta.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyxwpxv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qphheosn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2iihhkudw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnyhnoe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2imojenwf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpjvnsl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2twamqslt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrqtqfw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2trywmybg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iesxluvz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eanzpzam.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tubxsobl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqcfog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhaegt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dshxtnyj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2buiuqfrr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jirilleb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkkmik.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxcadze.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwkxjqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtvtqqv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzlgxfu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwoqqql.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnxopqv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhptrv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbaejs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2osoyrknw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtizobwq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rixbpvpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpbyyxf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrndtbi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2icckqanq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtjwwog.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gblbdxrd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzfwmng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emgmsrxd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlrgpbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhffhlh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvncryrd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oufooktb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2btqfxsxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2upggwmxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuzmrbb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jhinpyep.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbblfzu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2spcokkuz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dunoyigs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pabvpelj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ozymhoai.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yurflpru.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxgbhpx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2unatcbkh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhkobzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsupdfyl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmytrygn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxjswcr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2futbaqfb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnmnjk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2apuqucwm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xllzkcph.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2evwfhvzk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kicfinct.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlefvmp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvespif.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2krpswpir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnugbacn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzzajg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oimrbmle.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fftbpdwi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvzlrgo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tqckours.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuxpyro.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gffhlwjw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmbzxog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzilnni.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrekibaa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2chwzcewf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnupbsx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gajvrwcv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2islivbey.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtpvhet.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhwzmbl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhobiib.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlusaxr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ultsjuee.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzwsmhs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2owzmpdxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvscdbpp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sejxktxf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaobgkal.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cejoobmk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymcbszg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywnajc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbzttks.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mguvdtnb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kddimxfv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdecemxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbmkiho.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkcmsgt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfanpqt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2femfwero.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkzmqzq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpflgsv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scunmxis.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlzphge.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzzoyvy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2krosadxw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhasvtb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdfkxai.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2deponcxm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bukwzexq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsakthi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljejwdjz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvsuail.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uesonmxx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gopmqykd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iamccodx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhfszqg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yohzfyno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmanbr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzpuxok.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjfzxnf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvdyuff.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erlybcnz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwizymjl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxnpnx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpruzabz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdqqwut.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrbqkix.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2asuxblix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrzwqie.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjtyjph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcgqgrz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgcihsw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlkjmsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcwnkec.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhhxbhi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmywtjx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivvyca.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2notbkvuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rexmlxyi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvtagf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2haczxest.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfibxgfb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqkfysj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bepnodsu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2smywnmsk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2evdemafh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwshwbh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfxxvza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgujblku.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzlehe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mttbbkpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2acsexiyy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbtysqw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2enmijlwm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhoonxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vxntkpoi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2avdkntex.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcvjljn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hscwexts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtfpqnu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nsojnphv.html


<!-- 参考信息 -->