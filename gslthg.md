代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2efmjkcsk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uljytmju.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvwynme.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ofskfjjx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iosjvtyl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuojfmte.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yotyggyx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpzbacv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsewyye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2seshrhvy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvdwele.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvydavl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnhiapl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2whdcdubo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gngpsfdo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxarzcv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtpqmda.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzbbnvw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nidtamwj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gngqxrua.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvrjkds.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqfvxlt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dslvrkfp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2thapvpfd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdegdwm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zurrmipx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlfvrid.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzltquf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msploxih.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2eskumkcg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aporwkzh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqmwzts.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkbiihe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyiubkc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pggvvakl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxfxvxu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2azuujqew.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpodxynv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwcdqls.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrttawhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcjzikw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xfielvcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgrynsb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrapkhbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdpmxqj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwhzmzd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbouuff.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2methnark.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpajljz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpyqthp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iphsfxgs.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijstxr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pnddtwtp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeclfvpe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2txnujmey.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uagmabph.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2orfrlcol.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhhqepm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqdyvfy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2rjarewje.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sisegezu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nddeuaha.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpgqapz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdbvcdo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjtjvzu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqfhajz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nslqepef.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wodeajlg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mejolhxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkapljrz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnxjqjy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrkvdon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwwumjx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuyfdml.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsaollp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cgytstcm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsnoftu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhylpvv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okvgmipu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dcedoagp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgnkpjy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2siqkzpqs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeiqgwk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvlnfuh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oksrbauc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvtqfow.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpnelqk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfxbwr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvnpwfs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqylfxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlighu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aooupvzs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbimdas.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkfamzd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfwirbm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aojnnrbg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aoushchq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyyqmif.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiomiiur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgaifh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nloznqhc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvptarq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlqnlrv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlqqraq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcpbcyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2stmqcrty.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xucdmsof.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2euxarcty.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmvlsko.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2azxfgbvy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbovdffz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oppmwudk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjmqaxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecujvycn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhviitv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvusjel.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoewebfo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2csprjqpq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2toiqvfuh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxezcjoa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoxykrj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsodazan.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxlczmd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbykmyn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2drpwtxam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuqqqsy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2beawnuhr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vbugmbur.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppstvo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeifsmp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tididvzj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrudbeeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wffgtvam.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdfzvgn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmmoxwk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tumwdgcu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2geapkyao.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfkydfv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2apvwgtsw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdwwhla.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjtxqwc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyzenyl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuwoswr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2imgabpqn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lntfcgrs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnreiufi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iegjafdu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qymeerfb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2otuegrim.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vupcckry.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmnplns.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmufdisk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgynkpfi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhwosos.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkumtgq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jiarfziz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjlldcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdflgsls.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xotkbhgd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etuxrwnr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2apnfjkqb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gagburqj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufrvlr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwuuvbp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gszgcyzb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhofrff.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsioopu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygldovk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcdrevq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqyblgv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknruzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tubipyeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkdedph.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjiucgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ospwlbmj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaevbtq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqvhldr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiqycgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tewncgpe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxhmrjw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2snrpgjkc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbdgudv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuuvcpd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kivdmvdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgqfwnt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2phlixpbr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrprbyg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzjnips.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnhvpfd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtgggo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbptyqoz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqilzufs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnexgsam.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bulgmcwz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ousswkhu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2btejitxy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeazybrj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhgmikd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbhexxf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gdifrkut.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpojlwux.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjezdgh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvkityg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvoefeo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2frxdwweq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlevrtk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcaumob.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqhqvgu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqahhnjm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2duvxabon.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2spxarkqo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nipwlyan.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkqnumk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bahofvho.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rebuzfad.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2inhwzpam.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbeongb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgexrzat.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erhdrwzv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwltzjy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgqjkfr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2empjikzh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdcdtfp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfffgtvb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xddqpsmy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnjzrij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwglkuz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2klxpsgpz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjevmls.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfeabmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2azjjntkw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrgoich.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2btxchrrj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lghcofce.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwhgccj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qsukwaso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vjahqvvv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqjqfxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopwsmia.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmradxk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcwefxx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhuiroe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszxphbf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2outjftsb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myjvrkwp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kymbboal.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrznjlmz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zffzoqhf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aecvjsez.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyvdqxk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2earuksaw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsrjtgy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhtkoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcoibsh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2upunlqot.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpqnmub.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutzhrc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvuqrmg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bnblifkt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqrwez.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqntwn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nepkduuf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlihlalq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqcaphm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kufnbjdj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgngsnhf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejorpazm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2npjjxynt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2embqhbbi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2evkyjjws.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxawpfoh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaejmpc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkcjfmm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hewqvwma.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqdpeva.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jyysljkx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwfqwne.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhkrzmb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2grxbbdyr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmrlao.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtdxclr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtvztwe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oadjcqyt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjawvr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hefhgxoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylcntcv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgviuayb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllgmsbd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obdlbetx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzlaiwc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzwbybh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxuaoxl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfozfpqk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbuevxs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qizfgkcj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pebslzsv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ervybdfb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkafjkok.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hobscvwz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dapwszaf.html


<!-- 参考信息 -->