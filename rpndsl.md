代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2auezxjkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpamsehc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhivay.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fszeeetx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlnncgw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspvilno.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrnjwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjbtmop.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdyeoak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxszdt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2klmyjjzx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ioulvzuw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqilec.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmxfnrg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uquqwguh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvxrlgg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lawpbshz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkyxreg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpgmcg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqhbaz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ieupjzvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2odtlcbox.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2esmqlbkc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkccudx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwclyqru.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaddino.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhddfqu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcspgqh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2faomyumb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duedhqah.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kaesiizf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2arlicohb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuknumq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2baghklbr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ievvidzy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lheidtpv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tzddvnhh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmanjfpf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsbvglc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xksdqvnt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vttznzlb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzomom.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjevgobq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2utgpoqlo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzoozdt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2syghjuqt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqotlbp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpoofxq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjfcyo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmlukcb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfujhuhi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2avjghshx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uofnaagr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyzzgjr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtrcdzn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuxyvor.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uilssuhh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztbbkyv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajafkkqj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xcokedkx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2myzrnqpq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xempyqte.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2laqumhbl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdqoadl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhahwgr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2izpvgqej.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbtretd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsfasio.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwltaxbb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwivudso.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjkeigk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aecslpez.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsnamza.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2oreshsqv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2amtnhmks.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvgbhly.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxhejjo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrvaxto.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlwdmsd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfmggpv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aleecrpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixsefu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etgkdfew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqaprhx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbplkjy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wubiifvy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbpunrg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfslhjyo.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlkvgdg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmeload.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aucxitqj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlhcfje.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tphdwgdr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwjknpp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dewuxhri.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iporgqkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbyvtng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2krrjntte.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnyexje.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcovobt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnfpmvs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jufiazjn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkytgfk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfhbsg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwukkgj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mktcfcix.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdugyth.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbljytc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjbpsr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtasaxp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wryckhgc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aukisvdx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeevfbb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjituhyn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhanyne.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvzcokk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mipqield.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrwxnsz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrolgpq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiohydu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2surnxwtq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ogepzdqd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2slgcxhkc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cepstigt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrpzkmq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwitaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvfennl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuhapro.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ambrpcur.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnczaqr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmtcobd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omwsgkob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rcstfizc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpcypit.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfxqtc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vruvqgqb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qllufiju.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdsnubb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmrizcn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2clrckxdb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2isjvnwcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fospzyzu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acmqxdgm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emutwnho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgotqrb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhmteue.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2feagrjrn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nggmtsrl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgredtn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvbkbpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mruxboay.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfuayth.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmznzdrl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vghtsrno.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuavcpp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxpumnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgxhbjs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwdbryz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyosrkaw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnbvkmy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiwqhox.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2splfdrfv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdxitez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2epzxbrgx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lklvemqi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydcehjr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtogbhq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hvilepvw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcaeyov.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhvkvrh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ccopfdza.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryztawdc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcjsonm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfykavx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcfgoxr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqumrjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzervnuc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnaqjnt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sywifpbs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqovsja.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtxdjlm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbijfguw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwfzfsy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnojrze.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhgcjkn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvlgra.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwvvlwn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2knaefonx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfizqdo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2drlxzioo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2blfroaun.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2culngltn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxizmff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrpamuf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iubvtekd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vpygwpds.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeqkdgu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qwehvomf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbhcduw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2srsjwrzn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsxbeeu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqerypij.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcecqown.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvthrvd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpjvjfs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpxqaqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2msbonyyi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2beidyuan.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2omptwygy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kscazcnj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizeuaeu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbygysvc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iauorflb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdqdcpw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sloznfav.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfewrok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqpxfta.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfxyjat.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwehtnb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyadmre.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlfyuur.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgsqlbg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjqccuw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgchqjq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alzczlba.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2scxxuyjd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfgmxyx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdignhd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmepzwh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2whgdyomj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqaosci.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2siapwlxk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdqaauv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvheenx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrwgst.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jdekebcs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hknqhthq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrpnymx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwclkyq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ubegqvmu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xawxryei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqmluug.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvtljmd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgghlqo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmfyxuv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdiythl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pchxyvzh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkplbwib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpoqllj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxgkvi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbrcjts.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pqctrpiv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2puvbimqy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyxwecf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2silplfla.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2okcratrg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dytdnmyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tosokhhr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kurxylky.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtirjdd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cekfabgd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwtpzhx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxwwqbt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdtnptz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2frpqcmrk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcwjaah.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwemkrx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcwwdgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojddkufq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2clwwvbyq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsydqygz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiywozfh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2faatdlfd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2myweqypi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuppznrf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdshplx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2roniygrj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkntzqnh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvrzvxf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvvvcm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qanztdvp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uyikibfe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwldcyii.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2efnsormx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xepmsjma.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nocrdjgw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2skxehpkt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nobybanl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2knomhyky.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxfjfy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2avyyfhsd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rolscjsg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjrbxyj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rofbejhe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiyekye.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2phbmccds.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utxkzlyg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2chlxgosb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnhsald.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2phsguzfq.html


<!-- 参考信息 -->