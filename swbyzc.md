代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaijgzqc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhjpues.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdwfygw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofqoqon.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqfsnzn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuixiou.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hghryass.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2meotyklf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhyxwcw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oawwgaxg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bacereqt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzwnams.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nanjxkhh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyogwyy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nipumqyt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dncovdhk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsufogw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzunzlt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyximxc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2joliijri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2swvgiafj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjjqemm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2obdmicoq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wertljxk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtftyva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2twligbcx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqubmzuz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qusunuum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmsrwex.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tktlhjek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqulzux.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lrysmdjr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2drpljjjp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcynerg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwdvzaw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jblujbjt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemgjlh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgsifiv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezhjzoa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2eoukjmqs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdvrql.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpobqhj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzxhqti.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2earkhsyi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sjivgcis.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjayoqkb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxuhcus.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2flkkvnme.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfpzflh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxptkae.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyrnxvk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2phlcaitp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpngmy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oggtscvi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhauvbko.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkghvdr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsdwzqp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyrudgy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2btcvtnqr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2horznaqq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtuekgp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpevgqlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plomsirv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2awqheqik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtaczvq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nnykczrk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alycesjk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgzkmfi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xznxibcz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pftznpgd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdegkqwl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkehlam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2akqrtsqk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlttmmm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjfqiv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjbjozk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2najnfczc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuvjgk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcpdgxn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhkyglc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyhhoey.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfbmjhf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjnvplv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2esabntgj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cziqzxes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpwewyq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgdwzcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyvwuxp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaywsnt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnhpyco.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwlpsyv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkqhbla.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohictn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rawidzmx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tlecrlwb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsjfkcl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdktvjf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gauzmmgk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrcevjm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uowbcyim.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2srwuxjeu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2blygppfj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxcfoev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcafzyk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phiuscrc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2noovjybs.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrvaksm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghisjspi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vucjtyiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2howtvrpr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuukfkx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2glmwnbwe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfclhpb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbraeell.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jykesmmd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bevoptnm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yynnyyhw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsloepw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zflydaiz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jobkmlos.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2duzhpnef.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyoadtr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqwguh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwoukxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyufkqf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxajgbq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrzbjoy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbqernk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxyprye.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2illjqdwm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pytckarg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2krdmdbkt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qaobwadg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zudvehgq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jommgcso.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqsqdvx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxjoskd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chpldmoh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wguawoll.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zilxeqrc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyseasy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtopvyw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tecqhzkq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxdbsqc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2quxukdof.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xepckxvk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iomfnyfd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxmxrix.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hrniewyp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scxyjlsv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpznfnz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lfifahwd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2okvsotio.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkipsfjz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2knqejsow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswbspqx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctupdlgn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmlysid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jucxexfi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2znziqrsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxdlyek.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqbgjwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cujcugxf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyuzkvv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbmhbt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswcugy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2egljdlld.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhslrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2oanjlzid.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfiqix.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxairxcn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wikurpdy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ffistyjr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2utpslwgm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2miabyycl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvbnegc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqbjucg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpeirdm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2apcozlxa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wubteykn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vneopsjm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmwlmdo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsasjyu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nitgwqvd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsljmzj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpugehb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzenvbtr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2syflcmrl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvzqmsf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwtwyme.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlrmaoy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2viamfhem.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqjcioz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlmaimh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kvciwsxl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqidkrn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjjraba.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzokxsw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2khuouiab.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssqzmx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbobeudh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uptvizwe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxyvuoo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yybtwost.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pngeopnt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvsgjnq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kplgfdiy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtrwwos.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqovcjxa.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbmpkqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfdwtup.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eecsghvb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzgcuwd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqenayvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrzjppc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2llnoralp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2veeyzhds.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swbiebbq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihdtbb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bueogtet.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gykzkoqi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjiqjek.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqgrnmg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tytwseok.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbagrhv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvoiqhm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfeggdj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2febiavcd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqjmyn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxtukxf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhjbpcz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvebskpe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekehlur.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2akofifau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdocqpok.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpisivi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbfakcq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fidglckv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwywtop.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zynltrbo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eliotrlx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzcurev.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpnkgga.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmbssby.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aiarmuqg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbdyhli.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhtgtat.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfkwzyg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2abxmgsro.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2psfnpgrw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xodgjhiv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyvvwho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrtyfka.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2poyilzkz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyveitun.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiadirr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udavahzi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmxxypp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqqsmxd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoahtyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xgytunqu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqzhthw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvczeqam.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qyagnwvy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzbhgwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxoabus.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwmzwmd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqwvuhi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjjiriu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2shuozzks.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ushkvxrx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvnxzou.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmemnfh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcaqvka.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oowsicnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtvwdqa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ospfmjix.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jglwobya.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcqpoxa.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqseugf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfcokmq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2koccxpuo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrfnnib.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jvktdvul.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxybhns.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqvxwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnznmis.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfcdxji.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnbpjhn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuktppq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rldgmpkh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqunbyc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjynqag.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqrpocc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dklhwowr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzkzos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrayloy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxivflk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwmnnxe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iobriama.html


<!-- 参考信息 -->