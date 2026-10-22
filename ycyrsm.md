代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrixrka.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyjexlb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqkexof.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tffwpake.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzohvvzk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2naofpmzo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdruslz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsmklyf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqyyszb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukqtmj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixpkhd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjylfye.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sidvlcyk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxmejkp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkffyhpe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckuoiyg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2schstics.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxbxmng.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlprnld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yesucuxc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwjvexo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzrksgy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpotdmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyxuoxf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrlfrwq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcvglgy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2slaupssv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plyxqnkf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2byajjycx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mghfatwg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyowqcy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyvioyu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaeceow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugawdmja.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mprftwlh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2szzmukdt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2llfyuhin.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvbfrbl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdhxrxe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgxcbps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elacsvjx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyhytuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szoahpvz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fplmuung.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mghmzeye.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2daeehyva.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bkezpjls.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bleudgft.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2znffjvup.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnahdvv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlyoqvx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cfafrvwm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpzqxm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgcojan.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtzxunm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aypuurwr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epehzygs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxnwzbs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbkvwcr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwawdkt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsxduux.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgmljti.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtyuknz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvqmkdi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hehuqpja.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aumdwdiz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbvdzej.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrkyrqm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2beafywco.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkmeytt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pasdecth.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpbrxfr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkzaqtw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evqbowrv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pawcrwih.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gegpudyv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxaiksc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kndkrzrv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xscmxbjv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jwctdpnp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfthledn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aqegptof.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjgymrk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuggfub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pclbtmnm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsrnuee.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmziloc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miayherv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2llabbhut.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkugnbo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dosxlpil.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkpkgmu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpmvodd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaixeru.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeikjwy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrekhzl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cuauikcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdxfllm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnkzxei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxtwxd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcogyuk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpithrup.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvehkuv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xelhpprk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmzblzz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncenruuj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2njqsrrkw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sabsfspz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgcoezp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzfjpcd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrajduz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkclmgme.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkfwojh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlwwhsg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqdamyr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvetmbhz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzqseqv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhbxlmv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiucsbq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhxjvub.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrosdyx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gilbpokq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycugoyzi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcommpo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkjkexk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qusjqqjw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2daplxgqm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zfychhfm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqzhjxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2shquvvse.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhrsnj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fphyhioz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgexcscc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajtuigk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bajrtawv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqrgsfs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vyceoacw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdmyipt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfpdisz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wjankutf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfcijr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kemjwgup.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugwgdtk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdevuism.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvhjtjt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjdpbgl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpurnpf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urpuvxmz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgvbtrw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlimrbd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hofpaiex.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lptzwukn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vduuvgvk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtpdbmz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjxdcjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vlesgkes.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhzzhqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqldpkln.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhovuky.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svpxukqb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvrhduu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkojoxk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzjylyc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyqfhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdirahcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtlmra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtomnvo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkngdaxb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbrbabg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoxhukz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvaiula.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmqesak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaghfmib.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvynncv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tulqkhvd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2budbymlr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2htuddsrf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfonfjq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjgbltm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrepuiwp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqfsetg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbgsoer.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2opljfxzo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ottrbqsm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmymazfy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrxwjs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ipggtplv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyxlcvy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtwedqa.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oofwdkmq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyovcxgq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytytehuh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkluozqw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfzfldi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxvwhxf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2noxuijem.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdzegav.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzodmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeapksqf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvndml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsptsg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ytobjrfu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzosisl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2smfwrrpp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfylucm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiyraoo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpireehr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhxcicq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhfxbj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmfohcg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2baxtgihk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxpdebf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vprcgwha.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sslbxaew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrjqsba.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zakluyje.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxfyfvd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvnxvtx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lucbtebg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqluajyz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyvjwfi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkvqvdn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnbwkhy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkhbrzv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyeupre.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcxefiy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyzoiwn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bcspkhyi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrchyzf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdatdngu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrctdbgc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jqadkgqn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2stosjctk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgidaqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyybfwt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2goskonxv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gykonmrn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsenhdwj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrbewyv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2choyeyah.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqigogv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzgdxuo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eycuvttq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfhvphv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmrmakr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pzubkwat.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dagegqxz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2znmnqvyy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wetdyegu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osafcbbv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2agmubdil.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ragtazzl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwesqnv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jphhlbup.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aecdbjwz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lutnlpwg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbawzef.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytmmqpk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2klajvexf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iukwgqoo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkmkpuz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavxrlzm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eafngqsv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clgafpkm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfngbtq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyckhpuc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzlhpza.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwojrbj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2orjezrrh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplxylk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgrbrqt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuvenvg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wadoszqi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjkxpzr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onzcqltk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2diynrzfa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfodtcu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzycszik.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtnpyxw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqnihw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sziabcgk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhkroh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cratfbwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnbgboq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sairdake.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyneziu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcmksmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vagzgpuy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2untxzenq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcnytsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcyesnq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2djyftuyq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyfkfsv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eprsbujb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fszujauq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxpxcjx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loqyywze.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2teenitfw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yplsndhs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuzdpdm.html


<!-- 参考信息 -->