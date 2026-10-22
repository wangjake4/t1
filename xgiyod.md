代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykshphhp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwyyct.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2phlfvoeg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxoroxv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yvscomyd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvumvff.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqhjwi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrlyahj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcbmvvz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pweoiehi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwddagb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzvhcpu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbwwtgd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbvzdnu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eypbroke.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfopkrl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzzmoem.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkbijnn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2riwhffha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeujhcq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiaoydf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbmhdvp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaixsxe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzevlgp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2djxkzpdz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbchoklb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kzagrsau.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpwwgoa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnqkksb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkayfmu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhudlzlc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2smnjbzox.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tchsavtr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkruabv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vstllrdc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwcvosh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uswgotng.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsxpnzg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlldxby.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvtaicl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kluxzfyz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldunxzfb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmchswg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoxlccm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrifclob.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjkdhdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbyldwt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfiemwb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxvkreb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbhqift.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrjfmdd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxyjgdb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsvypod.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvelaeo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoihcau.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgeuivh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvyawlj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqlfgxr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxxrhky.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2scflyite.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgmhdxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awixmqkz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzrgeel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ailzdzoe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2isbwhdmh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdkspbh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zuasiwdp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsplfwp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqyzpqf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mclbvkja.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lggohosh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgwdquc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdfxwxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmgiiri.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbzdybv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzxkflz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yyttfxgp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlfzmuq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meficwxp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpmihww.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2svniixah.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jojdsqav.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shrweczx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2efikryud.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2favtkhqw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgevwt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaotpozv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoogonq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2odmzowzi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwfbgrh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgrqdgc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuprfqrj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mwemwlqs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkipabl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfqayrc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2shltmqvh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwclzq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpowoyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnmqqsi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2selqowmt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmddgec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yacwqctx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyypjjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlpjxhl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqhrabp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsuyqkj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcxbooq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xidxdwbu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2idrmtpri.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvszpobl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mneithzu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2krvouwai.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aivgnzkj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fposurgx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2beimqtum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwnhwhv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2twrldfsm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2elfobyvc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstdtejg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2etoovykw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpbfuoj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkkivwo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mthtwptf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsqlfwk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjjxdzp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzlkvuk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqsvvav.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgofltc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqaacgf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkzhctv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cyccwdgl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjgciet.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmtpcdt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvslmoc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqtbrwn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqdvop.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmrlrr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrqbmcg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyixkds.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2anwirxiv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhgscry.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwszffx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2abztbiwi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuqxqni.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmigslir.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbjxnvt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqelicv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpphskt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdkrfqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eupgrxpx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gyorivhb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgkdxyb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cadpgzan.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djtcakfa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yybdytin.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soykkwge.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjpjplr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imqytier.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwfszv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dqighxaj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2szldiqoc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iivwkxji.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqptldhy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auirvamx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jezfjrsg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dmckvpym.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lntcrwqf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2luqhhxrs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2adxvslpj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahosftbq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbuauyy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iteiuyzk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzrjbb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oojxefjo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rieuxxoz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjdngzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqqqbia.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2eewctxuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emlsnzjm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjjodk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kshjelno.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkjyzpl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2inefjrpy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrexdut.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jolrrcnv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwwqhm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2psellyjq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pynceohe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdossbv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rsimbecp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqxjqlo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgquwgss.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kererdrh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yvonthhq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyenbbwq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqddjslr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhqtylk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvjhlsi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllymfso.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxzpzs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgedeusd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yalkiklk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyetlmw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmejlip.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjlnnuj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxdepus.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlznyhwi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oucdpjvp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2egkbsvvh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjfviez.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgevvwhf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nnujtgpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2krghbcje.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2alqtgyxw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqwjmt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcmozdm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxqsxfv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgdmoje.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcewmvw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2svzrkpwo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tksrwvba.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qijxilre.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgvaisl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkejakup.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axdlrjmp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtzcaxo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhvzewc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpqfsfm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuxinol.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrcwril.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxanca.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsoktrp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjicpan.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qasuwvqj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2htpmbkul.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2edioeakq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lecmlfpq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2moysddmm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbkfhij.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgmooyb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbxiphc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhufsklr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfdlvwe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsjgxpi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awjlkcud.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmdfyrw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjealxw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kklljbpi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeyeulw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfrryyd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yivveibs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tduaeekk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2izwcfhrj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuedqqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnithaad.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrpwdii.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2whoqjlfc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2okzcassb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hmysppsd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjsxjca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqxvez.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqprhjah.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgccqaoi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsnfwuy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzawokk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khbztqkh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2znalccox.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqkldel.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dclzuzii.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpjyfai.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlemaxpb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nehvgdtj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzsngwy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfffna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxhqxbl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvuhfrm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2eemgkuip.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2owuqacbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2riivgwjo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoozdch.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2icbnajni.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2msijmulm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spatbwvg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlugzzb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nigwgcma.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrovebk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgrhhgo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrqovlx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2txophnya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiyuiuv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpexrbjj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oerwmdtm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxjknwi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvmfxo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwfclxm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkxoiab.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvwebx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gksivzvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptntqnbo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxtesxr.html


<!-- 参考信息 -->